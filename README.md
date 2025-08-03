# 🌿 GreenAura Plant API

Welcome to **GreenAura**, a free and open plant information API that provides detailed data for plant care including:

- ✅ Common & Scientific names  
- ✅ Soil type, water level, spacing  
- ✅ Temperature and pH requirements  
- ✅ Weed control, harvesting, post-harvest info  
- ✅ Image links and plant descriptions  

> Built for learners, developers, and nature lovers 💚

---

## 📡 API Base URL
https://greenaura-plant-api.onrender.com/plants
---

This is a **read-only REST API** powered by JSON Server.

---

## 🔎 Example Request

### `GET /plants`

Returns all available plant data in JSON format.

[![Run in Postman](https://run.pstmn.io/button.svg)](https://www.postman.com/collections/47284278-c5054992-5c3f-47ad-8689-34e3127ce802)
---

**Example using curl:**
```bash
curl https://greenaura-plant-api.onrender.com/plants
[
  {
    "Temperature": "31.1234212",
    "PH": "6.5",
    "Soil": "Well-drained Sandy  Soil",
    "Waterlevel": "High",
    "Space": "0.025",
    "Label": "Radish",
    "common name": "Radish",
    "Image Src": "https://i.postimg.cc/1tRCvXJk/radish.png",
    "Description": "Radish belongs to the family Brassicaceae..."
  },
  
]
...



**Author:**
mahamoni
