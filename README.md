<h1 align="center">HerbsPedia - API Documentation</h1>

## Introduction

This documentation provides details about the HerbsPedia REST API endpoints. The code is a Node.js with Express.js module that exposes many endpoints with specific routes

## Base URL

The base URL for almost all API endpoints is: `https://api-endpoint-dgonny5rzq-et.a.run.app/`

---

#### 1. Get All Plants

- _Endpoint:_ GET /api/plants
- _Description:_ Returns all available herbal plant data.
- _Response Body Example:_

  ```json
  {
        "id" :1,
        "kategory" : "Daun",
        "nama": "Belimbing Wuluh",
        "deskripsi": "Daun belimbing wuluh adalah bagian dari tanaman belimbing yang dikenal dengan aroma khasnya yang segar dan asam. Di samping digunakan luas dalam masakan tradisional untuk memberikan rasa dan aroma unik, daun belimbing wuluh juga memiliki manfaat kesehatan yang signifikan. Kandungan vitamin C yang tinggi dalam daun ini berperan penting dalam meningkatkan sistem kekebalan tubuh, melindungi sel-sel tubuh dari kerusakan oksidatif, serta membantu dalam proses penyembuhan luka. Selain itu, daun belimbing wuluh juga mengandung antioksidan yang membantu menangkal radikal bebas, serta memiliki sifat antiinflamasi yang membantu meredakan peradangan dalam tubuh.",
        "kegunaan": "Daun belimbing wuluh memiliki beragam manfaat kesehatan yang dapat memberikan kontribusi positif bagi tubuh. Selain sebagai bahan utama dalam masakan tradisional untuk memberikan rasa segar dan asam, daun belimbing wuluh kaya akan vitamin C yang membantu memperkuat sistem kekebalan tubuh. Vitamin C juga berperan dalam melindungi sel-sel tubuh dari kerusakan oksidatif serta mendukung proses penyembuhan luka. Selain itu, daun ini mengandung senyawa antioksidan yang membantu melawan radikal bebas dalam tubuh, menjaga kesehatan kulit, dan mengurangi risiko penyakit kronis seperti penyakit jantung dan diabetes. Kandungan antiinflamasi dalam daun belimbing wuluh juga dapat membantu meredakan peradangan dan mengurangi risiko peradangan kronis. Dengan begitu, mengonsumsi daun belimbing wuluh secara teratur dapat memberikan manfaat besar bagi kesehatan secara keseluruhan.",
        "gambar": "https://storage.googleapis.com/image-app/image/belimbing%20wuluh.png"
    },
    {
        "id" :2,
        "kategory" : "Daun",
        "nama": "Jambu Biji",
        "deskripsi": "Daun jambu biji memiliki berbagai khasiat kesehatan yang telah digunakan dalam pengobatan tradisional selama berabad-abad. Daun ini kaya akan vitamin C, serat, dan antioksidan yang penting untuk menjaga kesehatan tubuh. Vitamin C dalam daun jambu biji membantu meningkatkan sistem kekebalan tubuh, melindungi dari infeksi, dan mempercepat penyembuhan luka. Serat yang terdapat dalam daun jambu biji mendukung pencernaan yang sehat dan membantu mengontrol kadar gula darah, sementara antioksidan yang terkandung di dalamnya berfungsi melawan radikal bebas, melindungi sel-sel tubuh dari kerusakan, dan mengurangi risiko penyakit kronis. Selain itu, daun jambu biji juga dikenal memiliki sifat antiinflamasi dan antibakteri, yang dapat membantu meredakan peradangan dan melawan infeksi. Dengan berbagai manfaat ini, daun jambu biji merupakan tambahan berharga dalam upaya menjaga kesehatan secara alami.",
        "kegunaan": "Daun jambu biji tidak hanya digunakan sebagai bahan makanan tambahan dalam masakan atau sebagai obat tradisional, tetapi juga memiliki sejumlah manfaat kesehatan yang berharga. Kandungan nutrisi yang melimpah, termasuk vitamin C dan serat, menjadikan daun ini bermanfaat dalam menjaga kesehatan tubuh secara menyeluruh. Vitamin C dalam daun jambu biji membantu meningkatkan sistem kekebalan tubuh, memperkuat pertahanan tubuh terhadap infeksi dan penyakit. Selain itu, serat dalam daun jambu biji mendukung pencernaan yang sehat, membantu mengatur kadar gula darah, dan menjaga kesehatan jantung. Daun jambu biji juga mengandung senyawa antioksidan yang dapat melawan radikal bebas, membantu melindungi sel-sel tubuh dari kerusakan, dan memperlambat penuaan sel. Dengan demikian, konsumsi daun jambu biji secara teratur dapat memberikan manfaat signifikan bagi kesehatan dan kesejahteraan tubuh secara keseluruhan.",
        "gambar": "https://storage.googleapis.com/image-app/image/jambu%20biji.png"
    },
    {
        "id" :3,
        "kategory" : "Daun",
        "nama": "Jeruk Nipis",
        "deskripsi": "Daun jeruk nipis dikenal memiliki berbagai manfaat kesehatan yang membuatnya populer dalam pengobatan tradisional. Daun ini kaya akan vitamin C, flavonoid, dan berbagai senyawa fitokimia yang berfungsi sebagai antioksidan. Vitamin C yang terkandung dalam daun jeruk nipis membantu meningkatkan sistem kekebalan tubuh, melawan infeksi, dan mempercepat penyembuhan luka. Antioksidan dalam daun ini juga berperan dalam melindungi sel-sel tubuh dari kerusakan akibat radikal bebas, sehingga dapat membantu mencegah penuaan dini dan berbagai penyakit kronis. Selain itu, daun jeruk nipis memiliki sifat antiinflamasi dan antibakteri yang dapat meredakan peradangan dan membantu melawan infeksi bakteri. Penggunaan daun jeruk nipis dalam bentuk teh atau infus juga diketahui dapat membantu memperbaiki pencernaan dan menjaga kesehatan mulut. Dengan berbagai manfaat ini, daun jeruk nipis merupakan salah satu bahan alami yang berkhasiat untuk mendukung kesehatan tubuh.",
        "kegunaan": "menyembuhkan flu, terutama saat menghadapi influenza parah.",
        "gambar": "https://storage.googleapis.com/image-app/image/jeruk%20nipis.png"
    }

  ```

  ```

  ```

#### 2. Get Plant by ID

- _Endpoint:_ GET /api/plants/1
- _Description:_ Returns herbal plant data based on a specific ID.
- _Parameters:_
  - id: The unique ID of the herb you want to take.
- _Response Body Example:_

  ```json
  {
        "id" :1,
        "kategory" : "Daun",
        "nama": "Belimbing Wuluh",
        "deskripsi": "Daun belimbing wuluh adalah bagian dari tanaman belimbing yang dikenal dengan aroma khasnya yang segar dan asam. Di samping digunakan luas dalam masakan tradisional untuk memberikan rasa dan aroma unik, daun belimbing wuluh juga memiliki manfaat kesehatan yang signifikan. Kandungan vitamin C yang tinggi dalam daun ini berperan penting dalam meningkatkan sistem kekebalan tubuh, melindungi sel-sel tubuh dari kerusakan oksidatif, serta membantu dalam proses penyembuhan luka. Selain itu, daun belimbing wuluh juga mengandung antioksidan yang membantu menangkal radikal bebas, serta memiliki sifat antiinflamasi yang membantu meredakan peradangan dalam tubuh.",
        "kegunaan": "Daun belimbing wuluh memiliki beragam manfaat kesehatan yang dapat memberikan kontribusi positif bagi tubuh. Selain sebagai bahan utama dalam masakan tradisional untuk memberikan rasa segar dan asam, daun belimbing wuluh kaya akan vitamin C yang membantu memperkuat sistem kekebalan tubuh. Vitamin C juga berperan dalam melindungi sel-sel tubuh dari kerusakan oksidatif serta mendukung proses penyembuhan luka. Selain itu, daun ini mengandung senyawa antioksidan yang membantu melawan radikal bebas dalam tubuh, menjaga kesehatan kulit, dan mengurangi risiko penyakit kronis seperti penyakit jantung dan diabetes. Kandungan antiinflamasi dalam daun belimbing wuluh juga dapat membantu meredakan peradangan dan mengurangi risiko peradangan kronis. Dengan begitu, mengonsumsi daun belimbing wuluh secara teratur dapat memberikan manfaat besar bagi kesehatan secara keseluruhan.",
        "gambar": "https://storage.googleapis.com/image-app/image/belimbing%20wuluh.png"
    }


  ```

  ```

  ```

- _Error Handling:_
  - If a plant with the requested ID is not found, the API will respond with a 404 status and an error message.

### The Usage

- Make sure the server is running with the index.js node running.
- To access plant data, use an endpoint that suits your application or integration needs.
