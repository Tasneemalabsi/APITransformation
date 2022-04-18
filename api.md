
{
	"info": {
		"_postman_id": "649954a0-0780-4ff1-afb3-9ab4b7f94736",
		"name": "Birth Certificate Service_v1",
		"description": "> This Collection Contain Sample requests for Birth_Certiicate_Service\n\nIt Contains the following requests:\n\n*   Get Applicant Data\n*   Get Beneficiary Birth Data\n*   Get Fees\n*   Get prerequisites\n*   Get List Of Countries\n*   Get List Of Martial Status\n*   Get List Of Cites\n*   Get List Of Departments",
		"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json"
	},
	"item": [
		{
			"name": "Get Martial Status",
			"request": {
				"method": "POST",
				"header": [],
				"url": {
					"raw": "https://10.0.52.241/birthcertificate/martialstatus",
					"protocol": "https",
					"host": [
						"10",
						"0",
						"52",
						"241"
					],
					"path": [
						"birthcertificate",
						"martialstatus"
					]
				},
				"description": "API endpoint to **Get list of martial status** from the system .\n\n> A Successful API Request Will result in a **HTTP 200** status code ."
			},
			"response": [
				{
					"name": "Get Martial Status",
					"originalRequest": {
						"method": "POST",
						"header": [],
						"url": {
							"raw": "https://10.0.52.241/birthcertificate/martialstatus",
							"protocol": "https",
							"host": [
								"10",
								"0",
								"52",
								"241"
							],
							"path": [
								"birthcertificate",
								"martialstatus"
							]
						}
					},
					"status": "OK",
					"code": 200,
					"_postman_previewlanguage": "json",
					"header": [
						{
							"key": "Date",
							"value": "Sun, 27 Mar 2022 08:02:07 GMT"
						},
						{
							"key": "Server",
							"value": "Apache/2.4.28 (Win64) OpenSSL/1.1.0f"
						},
						{
							"key": "X-Frame-Options",
							"value": "SAMEORIGIN"
						},
						{
							"key": "Cache-Control",
							"value": "no-store"
						},
						{
							"key": "Content-Type",
							"value": "application/json;charset=utf-8"
						},
						{
							"key": "Content-Length",
							"value": "2584"
						},
						{
							"key": "Keep-Alive",
							"value": "timeout=5, max=100"
						},
						{
							"key": "Connection",
							"value": "Keep-Alive"
						},
						{
							"key": "Set-Cookie",
							"value": "COOKI3=ffffffff09082ae145525d5f4f58455e445a4a42378b;expires=Sun, 27-Mar-2022 08:04:07 GMT;path=/;secure;httponly"
						}
					],
					"cookie": [],
					"body": "[\n    {\n        \"Code\": \"02\",\n        \"DescriptionArabic\": \"متزوج/ متزوجة\",\n        \"DescriptionEnglish\": \"Married\",\n        \"Description\": \"متزوج/ متزوجة\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-03-20T13:28:13.441Z\",\n        \"createdDate\": \"2018-09-03T13:04:56.283Z\"\n    },\n    {\n        \"Code\": \"03\",\n        \"DescriptionArabic\": \"مطلق / مطلقة\",\n        \"DescriptionEnglish\": \"DIVORCE\",\n        \"Description\": \"مطلق / مطلقة\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-03-08T11:01:00.017Z\",\n        \"createdDate\": \"2018-09-03T13:05:12.600Z\"\n    },\n    {\n        \"Code\": \"04\",\n        \"DescriptionArabic\": \"ارمل / ارملة\",\n        \"DescriptionEnglish\": \"WIDOWED\",\n        \"Description\": \"ارمل / ارملة\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-03-16T11:29:36.394Z\",\n        \"createdDate\": \"2018-09-03T13:05:22.088Z\"\n    },\n    {\n        \"Code\": \"05\",\n        \"DescriptionArabic\": \"متزوجه من اجنبي\",\n        \"DescriptionEnglish\": \"MARRIAGE FROM FOREIGN\",\n        \"Description\": \"متزوجه من اجنبي\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-12-24T08:36:35.994Z\",\n        \"createdDate\": \"2018-09-03T13:05:31.816Z\"\n    },\n    {\n        \"Code\": \"06\",\n        \"DescriptionArabic\": \"ارملة الاجنبي\",\n        \"DescriptionEnglish\": \"WIDOWED FOREIGN\",\n        \"Description\": \"ارملة الاجنبي\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-12-17T09:32:39.880Z\",\n        \"createdDate\": \"2018-09-03T13:05:44.967Z\"\n    },\n    {\n        \"Code\": \"07\",\n        \"DescriptionArabic\": \"زوجة المفقود\",\n        \"DescriptionEnglish\": \"MISS WIFE\",\n        \"Description\": \"زوجة المفقود\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-02-28T07:40:09.100Z\",\n        \"createdDate\": \"2018-09-03T13:05:58.616Z\"\n    },\n    {\n        \"Code\": \"10\",\n        \"DescriptionArabic\": \"زوجة الغائب\",\n        \"DescriptionEnglish\": \"The Absent Wife\",\n        \"Description\": \"زوجة الغائب\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T13:06:48.009Z\",\n        \"createdDate\": \"2018-09-03T13:06:33.270Z\"\n    },\n    {\n        \"Code\": \"11\",\n        \"DescriptionArabic\": \"زوجة أجنبي ابناء اردني\",\n        \"DescriptionEnglish\": \"FOREIGN WIFE JOR SON\",\n        \"Description\": \"زوجة أجنبي ابناء اردني\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-04-14T09:41:43.519Z\",\n        \"createdDate\": \"2018-09-03T13:07:00.270Z\"\n    },\n    {\n        \"Code\": \"01\",\n        \"DescriptionArabic\": \"أعزب/ عزباء\",\n        \"DescriptionEnglish\": \"Single\",\n        \"Description\": \"أعزب/ عزباء\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-03-21T09:23:20.714Z\",\n        \"createdDate\": \"2020-07-29T08:02:56.202Z\"\n    },\n    {\n        \"Code\": \"Saepe repudiandae necessitatibus accusantium molestiae aspernatur a quidem aspernatur aperiam\",\n        \"DescriptionArabic\": \"الوصف بالعربي\",\n        \"DescriptionEnglish\": \"Et corporis magna nemo eos asperiores voluptate ipsam magnam eum veniam sequi\",\n        \"Description\": \"الوصف بالعربي\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-09-14T11:05:33.078Z\",\n        \"createdDate\": \"2021-09-14T11:05:22.516Z\"\n    }\n]"
				}
			]
		},
		{
			"name": "Get List Of City",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "\r\n{\r\n  \"ISO_Code\": \"001\"\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://10.0.52.241/birthcertificate/cities",
					"protocol": "https",
					"host": [
						"10",
						"0",
						"52",
						"241"
					],
					"path": [
						"birthcertificate",
						"cities"
					]
				},
				"description": "API endpoint to **Get list of Cities** in the system .\n\n> A Successful API Request Will result in a **HTTP 200** status code ."
			},
			"response": [
				{
					"name": "Get List Of City",
					"originalRequest": {
						"method": "POST",
						"header": [],
						"body": {
							"mode": "raw",
							"raw": "\r\n{\r\n  \"ISO_Code\": \"001\"\r\n}",
							"options": {
								"raw": {
									"language": "json"
								}
							}
						},
						"url": {
							"raw": "https://10.0.52.241/birthcertificate/cities",
							"protocol": "https",
							"host": [
								"10",
								"0",
								"52",
								"241"
							],
							"path": [
								"birthcertificate",
								"cities"
							]
						}
					},
					"status": "OK",
					"code": 200,
					"_postman_previewlanguage": "json",
					"header": [
						{
							"key": "Date",
							"value": "Sun, 27 Mar 2022 07:56:10 GMT"
						},
						{
							"key": "Server",
							"value": "Apache/2.4.28 (Win64) OpenSSL/1.1.0f"
						},
						{
							"key": "X-Frame-Options",
							"value": "SAMEORIGIN"
						},
						{
							"key": "Cache-Control",
							"value": "no-store"
						},
						{
							"key": "Content-Type",
							"value": "application/json;charset=utf-8"
						},
						{
							"key": "Content-Length",
							"value": "2503"
						},
						{
							"key": "Keep-Alive",
							"value": "timeout=5, max=100"
						},
						{
							"key": "Connection",
							"value": "Keep-Alive"
						},
						{
							"key": "Set-Cookie",
							"value": "COOKI3=ffffffff09082ae145525d5f4f58455e445a4a42378b;expires=Sun, 27-Mar-2022 07:58:10 GMT;path=/;secure;httponly"
						}
					],
					"cookie": [],
					"body": "[\n    {\n        \"Code\": \"13\",\n        \"DescriptionArabic\": \"الزرقاء\",\n        \"DescriptionEnglish\": \"Zarqa\",\n        \"Description\": \"الزرقاء\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-02-17T13:14:34.485Z\",\n        \"createdDate\": \"2018-09-03T12:54:58.303Z\"\n    },\n    {\n        \"Code\": \"21\",\n        \"DescriptionArabic\": \"اربد\",\n        \"DescriptionEnglish\": \"Irbid\",\n        \"Description\": \"اربد\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-03-23T09:14:38.770Z\",\n        \"createdDate\": \"2018-09-03T12:54:58.303Z\"\n    },\n    {\n        \"Code\": \"11\",\n        \"DescriptionArabic\": \"العاصمة\",\n        \"DescriptionEnglish\": \"Amman\",\n        \"Description\": \"العاصمة\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-02-17T13:14:36.329Z\",\n        \"createdDate\": \"2018-09-03T12:54:58.303Z\"\n    },\n    {\n        \"Code\": \"22\",\n        \"DescriptionArabic\": \"المفرق\",\n        \"DescriptionEnglish\": \"Mafraq\",\n        \"Description\": \"المفرق\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-03-16T11:54:15.594Z\",\n        \"createdDate\": \"2018-09-03T12:54:58.303Z\"\n    },\n    {\n        \"Code\": \"23\",\n        \"DescriptionArabic\": \"جرش\",\n        \"DescriptionEnglish\": \"Jerash\",\n        \"Description\": \"جرش\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-11-18T13:49:35.840Z\",\n        \"createdDate\": \"2018-09-03T12:54:58.303Z\"\n    },\n    {\n        \"Code\": \"14\",\n        \"DescriptionArabic\": \"مأدبا\",\n        \"DescriptionEnglish\": \"Madaba\",\n        \"Description\": \"مأدبا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-11-25T12:32:58.136Z\",\n        \"createdDate\": \"2018-09-03T12:54:58.303Z\"\n    },\n    {\n        \"Code\": \"12\",\n        \"DescriptionArabic\": \"البلقاء\",\n        \"DescriptionEnglish\": \"Balqa\",\n        \"Description\": \"البلقاء\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-07-29T09:44:56.315Z\",\n        \"createdDate\": \"2018-09-03T12:54:58.303Z\"\n    },\n    {\n        \"Code\": \"32\",\n        \"DescriptionArabic\": \"الطفيله\",\n        \"DescriptionEnglish\": \"Tafilah\",\n        \"Description\": \"الطفيله\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-11-25T12:18:56.791Z\",\n        \"createdDate\": \"2018-09-03T12:54:58.303Z\"\n    },\n    {\n        \"Code\": \"33\",\n        \"DescriptionArabic\": \"معان\",\n        \"DescriptionEnglish\": \"Ma'an\",\n        \"Description\": \"معان\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-11-25T12:33:01.874Z\",\n        \"createdDate\": \"2018-09-03T12:54:58.303Z\"\n    },\n    {\n        \"Code\": \"24\",\n        \"DescriptionArabic\": \"عجلون\",\n        \"DescriptionEnglish\": \"Ajloun\",\n        \"Description\": \"عجلون\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-12-20T15:07:35.075Z\",\n        \"createdDate\": \"2018-09-03T12:54:58.303Z\"\n    },\n    {\n        \"Code\": \"31\",\n        \"DescriptionArabic\": \"الكرك\",\n        \"DescriptionEnglish\": \"Karak\",\n        \"Description\": \"الكرك\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-11-25T10:54:59.389Z\",\n        \"createdDate\": \"2018-09-03T12:54:58.303Z\"\n    },\n    {\n        \"Code\": \"34\",\n        \"DescriptionArabic\": \"العقبة\",\n        \"DescriptionEnglish\": \"Aqaba\",\n        \"Description\": \"العقبة\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-19T07:44:35.961Z\",\n        \"createdDate\": \"2018-09-03T12:54:58.303Z\"\n    }\n]"
				},
				{
					"name": "Get List Of City_ErrorResponse",
					"originalRequest": {
						"method": "POST",
						"header": [],
						"body": {
							"mode": "raw",
							"raw": "\r\n{\r\n  \"ISO_Code\": \"\"\r\n}",
							"options": {
								"raw": {
									"language": "json"
								}
							}
						},
						"url": {
							"raw": "https://10.0.52.241/birthcertificate/cities",
							"protocol": "https",
							"host": [
								"10",
								"0",
								"52",
								"241"
							],
							"path": [
								"birthcertificate",
								"cities"
							]
						}
					},
					"status": "The Entered ISO_Code is not for Jordan , Jordan ISO_Code : 001",
					"code": 400,
					"_postman_previewlanguage": "json",
					"header": [
						{
							"key": "Date",
							"value": "Sun, 27 Mar 2022 07:58:13 GMT"
						},
						{
							"key": "Server",
							"value": "Apache/2.4.28 (Win64) OpenSSL/1.1.0f"
						},
						{
							"key": "X-Frame-Options",
							"value": "SAMEORIGIN"
						},
						{
							"key": "Cache-Control",
							"value": "no-store"
						},
						{
							"key": "Content-Type",
							"value": "application/json;charset=utf-8"
						},
						{
							"key": "Content-Length",
							"value": "75"
						},
						{
							"key": "Connection",
							"value": "close"
						},
						{
							"key": "Set-Cookie",
							"value": "COOKI3=ffffffff09082ae145525d5f4f58455e445a4a42378b;expires=Sun, 27-Mar-2022 08:00:13 GMT;path=/;secure;httponly"
						}
					],
					"cookie": [],
					"body": "{\n    \"Error\": \"The Entered ISO_Code is not for Jordan , Jordan ISO_Code : 001\"\n}"
				}
			]
		},
		{
			"name": "Get List Of Departements",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\r\n\"IsoCode\":\"001\",\r\n\"ServiceType\":\"Birth_Certificate\",\r\n\"DepartmentType\":\"02\"\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://10.0.52.241/birthcertificate/departments",
					"protocol": "https",
					"host": [
						"10",
						"0",
						"52",
						"241"
					],
					"path": [
						"birthcertificate",
						"departments"
					]
				},
				"description": "API endpoint to **Get list of Departments** in the system .\n\n> A Successful API Request Will result in a **HTTP 200** status code ."
			},
			"response": [
				{
					"name": "Get List Of Departements",
					"originalRequest": {
						"method": "POST",
						"header": [],
						"body": {
							"mode": "raw",
							"raw": "{\r\n    \"IsoCode\": \"001\",\r\n    \"ServiceType\": \"Birth_Certificate\",\r\n    \"DepartmentType\": \"02\"\r\n}",
							"options": {
								"raw": {
									"language": "json"
								}
							}
						},
						"url": {
							"raw": "https://10.0.52.241/birthcertificate/departments",
							"protocol": "https",
							"host": [
								"10",
								"0",
								"52",
								"241"
							],
							"path": [
								"birthcertificate",
								"departments"
							]
						}
					},
					"status": "Ok",
					"code": 200,
					"_postman_previewlanguage": "json",
					"header": [
						{
							"key": "Date",
							"value": "Sun, 27 Mar 2022 07:34:26 GMT"
						},
						{
							"key": "Server",
							"value": "Apache/2.4.28 (Win64) OpenSSL/1.1.0f"
						},
						{
							"key": "X-Frame-Options",
							"value": "SAMEORIGIN"
						},
						{
							"key": "Cache-Control",
							"value": "no-store"
						},
						{
							"key": "Content-Type",
							"value": "application/json;charset=utf-8"
						},
						{
							"key": "Content-Length",
							"value": "12355"
						},
						{
							"key": "Keep-Alive",
							"value": "timeout=5, max=100"
						},
						{
							"key": "Connection",
							"value": "Keep-Alive"
						},
						{
							"key": "Set-Cookie",
							"value": "COOKI3=ffffffff09082ae145525d5f4f58455e445a4a42378b;expires=Sun, 27-Mar-2022 07:36:26 GMT;path=/;secure;httponly"
						}
					],
					"cookie": [],
					"body": "[\n    {\n        \"Code\": \"201\",\n        \"HasEmployee\": false,\n        \"HasManager\": false,\n        \"DepartmentType\": \"CSPD_Office\",\n        \"MainOfficeInd\": false,\n        \"PrintingInd\": true,\n        \"AddressDetails\": \"السلط   تلفون 05554921\",\n        \"AdditionalServiceFees\": 0,\n        \"ArabicIssuanceAuthority\": \"السلط\",\n        \"EnglishIssuanceAuthority\": \"AL SALT\",\n        \"PrintingExport\": \"1\",\n        \"DepartmentTypeExport\": \"1\",\n        \"EmbassyCode\": \"201\",\n        \"OnlineInd\": false,\n        \"CivilOfficeInd\": true,\n        \"InternalOffice\": false,\n        \"PrintingButton\": \"ViewAndPrinting\",\n        \"PassportFileInd\": true,\n        \"CheckIPAddress\": false,\n        \"embassyInd\": false,\n        \"DescriptionArabic\": \"السلط\",\n        \"DescriptionEnglish\": \"AL SALT\",\n        \"Description\": \"السلط\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-12-27T16:09:42.077Z\",\n        \"createdDate\": \"2018-09-05T19:26:56.329Z\"\n    },\n    {\n        \"Code\": \"701\",\n        \"HasEmployee\": false,\n        \"HasManager\": false,\n        \"DepartmentType\": \"CSPD_Office\",\n        \"MainOfficeInd\": false,\n        \"PrintingInd\": true,\n        \"AddressDetails\": \"الطفيله   تلفون 03341116\",\n        \"AdditionalServiceFees\": 0,\n        \"ArabicIssuanceAuthority\": \"الطفيلة\",\n        \"EnglishIssuanceAuthority\": \"AL TAFILA\",\n        \"PrintingExport\": \"1\",\n        \"DepartmentTypeExport\": \"1\",\n        \"EmbassyCode\": \"701\",\n        \"OnlineInd\": false,\n        \"CivilOfficeInd\": true,\n        \"InternalOffice\": false,\n        \"PrintingButton\": \"ViewAndPrinting\",\n        \"PassportFileInd\": true,\n        \"CheckIPAddress\": false,\n        \"embassyInd\": false,\n        \"DescriptionArabic\": \"الطفيلة\",\n        \"DescriptionEnglish\": \"AL TAFILA\",\n        \"Description\": \"الطفيلة\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-12-27T16:09:45.428Z\",\n        \"createdDate\": \"2018-09-05T19:26:56.329Z\"\n    },\n    {\n        \"Code\": \"601\",\n        \"HasEmployee\": false,\n        \"HasManager\": false,\n        \"DepartmentType\": \"CSPD_Office\",\n        \"MainOfficeInd\": true,\n        \"PrintingInd\": true,\n        \"AddressDetails\": \"العقبه    تلفون 03313864\",\n        \"AdditionalServiceFees\": 0,\n        \"ArabicIssuanceAuthority\": \"العقبة\",\n        \"EnglishIssuanceAuthority\": \"AL AQABA\",\n        \"PrintingExport\": \"1\",\n        \"DepartmentTypeExport\": \"1\",\n        \"EmbassyCode\": \"601\",\n        \"OnlineInd\": false,\n        \"CivilOfficeInd\": true,\n        \"InternalOffice\": true,\n        \"PrintingButton\": \"Printing\",\n        \"PassportFileInd\": true,\n        \"CheckIPAddress\": false,\n        \"embassyInd\": false,\n        \"DescriptionArabic\": \"العقبة\",\n        \"DescriptionEnglish\": \"AL AQABA\",\n        \"Description\": \"العقبة\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-09-06T14:29:59.316Z\",\n        \"createdDate\": \"2018-09-05T19:26:56.334Z\"\n    },\n    {\n        \"Code\": \"001\",\n        \"HasEmployee\": false,\n        \"HasManager\": false,\n        \"DepartmentType\": \"CSPD_Office\",\n        \"MainOfficeInd\": false,\n        \"PrintingInd\": true,\n        \"AddressDetails\": \"جبل عمان / الدوار الاول    تلفون  636370\",\n        \"AdditionalServiceFees\": 0,\n        \"ArabicIssuanceAuthority\": \"عمان الغربيه\",\n        \"EnglishIssuanceAuthority\": \"AMMAN\",\n        \"PrintingExport\": \"1\",\n        \"DepartmentTypeExport\": \"1\",\n        \"EmbassyCode\": \"001\",\n        \"OnlineInd\": false,\n        \"CivilOfficeInd\": true,\n        \"InternalOffice\": false,\n        \"PrintingButton\": \"Printing\",\n        \"PassportFileInd\": true,\n        \"CheckIPAddress\": false,\n        \"embassyInd\": false,\n        \"DescriptionArabic\": \"عمان الغربيه\",\n        \"DescriptionEnglish\": \"AMMAN\",\n        \"Description\": \"عمان الغربيه\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-02-17T13:14:35.204Z\",\n        \"createdDate\": \"2018-09-05T19:26:56.334Z\"\n    },\n    {\n        \"Code\": \"003\",\n        \"HasEmployee\": false,\n        \"HasManager\": false,\n        \"DepartmentType\": \"CSPD_Office\",\n        \"MainOfficeInd\": false,\n        \"PrintingInd\": true,\n        \"AddressDetails\": \"عمان / المحطه   تلفون    4882968\",\n        \"AdditionalServiceFees\": 0,\n        \"ArabicIssuanceAuthority\": \"ماركا\",\n        \"EnglishIssuanceAuthority\": \"MARKA\",\n        \"PrintingExport\": \"1\",\n        \"DepartmentTypeExport\": \"1\",\n        \"EmbassyCode\": \"003\",\n        \"OnlineInd\": false,\n        \"CivilOfficeInd\": true,\n        \"InternalOffice\": false,\n        \"PrintingButton\": \"Printing\",\n        \"PassportFileInd\": true,\n        \"CheckIPAddress\": false,\n        \"embassyInd\": false,\n        \"DescriptionArabic\": \"ماركا\",\n        \"DescriptionEnglish\": \"MARKA\",\n        \"Description\": \"ماركا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-02-17T13:14:33.626Z\",\n        \"createdDate\": \"2018-09-05T19:26:56.334Z\"\n    },\n    {\n        \"Code\": \"005\",\n        \"HasEmployee\": false,\n        \"HasManager\": false,\n        \"DepartmentType\": \"CSPD_Office\",\n        \"MainOfficeInd\": false,\n        \"PrintingInd\": true,\n        \"AddressDetails\": \"صويلح   تلفون  5357428\",\n        \"AdditionalServiceFees\": 0,\n        \"ArabicIssuanceAuthority\": \"صويلح\",\n        \"EnglishIssuanceAuthority\": \"SWEILEH\",\n        \"PrintingExport\": \"1\",\n        \"DepartmentTypeExport\": \"1\",\n        \"EmbassyCode\": \"005\",\n        \"OnlineInd\": false,\n        \"CivilOfficeInd\": true,\n        \"InternalOffice\": true,\n        \"PrintingButton\": \"Printing\",\n        \"PassportFileInd\": true,\n        \"CheckIPAddress\": false,\n        \"embassyInd\": false,\n        \"DescriptionArabic\": \"صويلح\",\n        \"DescriptionEnglish\": \"SWEILEH\",\n        \"Description\": \"صويلح\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-03-24T06:19:58.063Z\",\n        \"createdDate\": \"2018-09-05T19:26:56.334Z\"\n    },\n    {\n        \"Code\": \"101\",\n        \"HasEmployee\": false,\n        \"HasManager\": false,\n        \"DepartmentType\": \"CSPD_Office\",\n        \"MainOfficeInd\": false,\n        \"PrintingInd\": true,\n        \"AddressDetails\": \"الزرقاء   تلفون 09983821\",\n        \"AdditionalServiceFees\": 0,\n        \"ArabicIssuanceAuthority\": \"الزرقاء\",\n        \"EnglishIssuanceAuthority\": \"ZARQA\",\n        \"PrintingExport\": \"1\",\n        \"DepartmentTypeExport\": \"1\",\n        \"EmbassyCode\": \"101\",\n        \"OnlineInd\": false,\n        \"CivilOfficeInd\": true,\n        \"InternalOffice\": false,\n        \"PrintingButton\": \"ViewAndPrinting\",\n        \"PassportFileInd\": true,\n        \"CheckIPAddress\": false,\n        \"embassyInd\": false,\n        \"DescriptionArabic\": \"الزرقاء\",\n        \"DescriptionEnglish\": \"ZARQA\",\n        \"Description\": \"الزرقاء\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-03-08T11:09:18.989Z\",\n        \"createdDate\": \"2018-09-05T19:26:56.334Z\"\n    },\n    {\n        \"Code\": \"009\",\n        \"HasEmployee\": false,\n        \"HasManager\": false,\n        \"DepartmentType\": \"CSPD_Office\",\n        \"MainOfficeInd\": false,\n        \"PrintingInd\": true,\n        \"AddressDetails\": \"سحاب    تلفون 721175\",\n        \"AdditionalServiceFees\": 0,\n        \"ArabicIssuanceAuthority\": \"سحاب\",\n        \"EnglishIssuanceAuthority\": \"SAHAB\",\n        \"PrintingExport\": \"1\",\n        \"DepartmentTypeExport\": \"1\",\n        \"EmbassyCode\": \"009\",\n        \"OnlineInd\": false,\n        \"CivilOfficeInd\": true,\n        \"InternalOffice\": false,\n        \"PrintingButton\": \"ViewAndPrinting\",\n        \"PassportFileInd\": true,\n        \"CheckIPAddress\": false,\n        \"embassyInd\": false,\n        \"DescriptionArabic\": \"سحاب\",\n        \"DescriptionEnglish\": \"SAHAB\",\n        \"Description\": \"سحاب\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-09-02T13:30:06.110Z\",\n        \"createdDate\": \"2018-09-05T19:26:56.334Z\"\n    },\n    {\n        \"Code\": \"006\",\n        \"HasEmployee\": false,\n        \"HasManager\": false,\n        \"DepartmentType\": \"CSPD_Office\",\n        \"IP_Address_From\": \"10.69.10.70\",\n        \"MainOfficeInd\": false,\n        \"PrintingInd\": true,\n        \"AddressDetails\": \"جبل الحسين/عمان   تلفون 4610278\",\n        \"AdditionalServiceFees\": 0,\n        \"IP_Address_To\": \"10.69.10.76\",\n        \"ArabicIssuanceAuthority\": \"جبل الحسين\",\n        \"EnglishIssuanceAuthority\": \"JABAL ALHUSSEIN\",\n        \"PrintingExport\": \"1\",\n        \"DepartmentTypeExport\": \"1\",\n        \"EmbassyCode\": \"004\",\n        \"OnlineInd\": false,\n        \"CivilOfficeInd\": true,\n        \"InternalOffice\": false,\n        \"PrintingButton\": \"ViewAndPrinting\",\n        \"PassportFileInd\": false,\n        \"CheckIPAddress\": false,\n        \"embassyInd\": false,\n        \"DescriptionArabic\": \"جبل الحسين\",\n        \"DescriptionEnglish\": \"JABAL ALHUSSEIN\",\n        \"Description\": \"جبل الحسين\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-03-21T09:23:20.741Z\",\n        \"createdDate\": \"2018-09-05T19:26:56.335Z\"\n    },\n    {\n        \"Code\": \"004\",\n        \"HasEmployee\": false,\n        \"HasManager\": false,\n        \"DepartmentType\": \"CSPD_Office\",\n        \"MainOfficeInd\": true,\n        \"PrintingInd\": true,\n        \"AddressDetails\": \"وادي السير   تلفون  814407\",\n        \"AdditionalServiceFees\": 0,\n        \"ArabicIssuanceAuthority\": \"وادي السير \",\n        \"EnglishIssuanceAuthority\": \"wadi alsir\",\n        \"PrintingExport\": \"1\",\n        \"DepartmentTypeExport\": \"1\",\n        \"EmbassyCode\": \"005\",\n        \"OnlineInd\": false,\n        \"CivilOfficeInd\": true,\n        \"InternalOffice\": false,\n        \"PrintingButton\": \"Printing\",\n        \"PassportFileInd\": true,\n        \"CheckIPAddress\": false,\n        \"embassyInd\": false,\n        \"DescriptionArabic\": \"وادي السير\",\n        \"DescriptionEnglish\": \"WADI ALSIR\",\n        \"Description\": \"وادي السير\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-02-17T13:14:36.313Z\",\n        \"createdDate\": \"2018-09-05T19:26:56.335Z\"\n    },\n    {\n        \"Code\": \"002\",\n        \"HasEmployee\": false,\n        \"HasManager\": false,\n        \"DepartmentType\": \"CSPD_Office\",\n        \"MainOfficeInd\": false,\n        \"PrintingInd\": true,\n        \"AddressDetails\": \"عمان / دوار الشرق الاوسط   تلفون 4754932\",\n        \"AdditionalServiceFees\": 0,\n        \"ArabicIssuanceAuthority\": \"الاشرفيه\",\n        \"EnglishIssuanceAuthority\": \"AL ASHRAFEA\",\n        \"PrintingExport\": \"1\",\n        \"DepartmentTypeExport\": \"1\",\n        \"EmbassyCode\": \"002\",\n        \"OnlineInd\": false,\n        \"CivilOfficeInd\": true,\n        \"InternalOffice\": false,\n        \"PrintingButton\": \"Printing\",\n        \"PassportFileInd\": false,\n        \"CheckIPAddress\": false,\n        \"embassyInd\": false,\n        \"DescriptionArabic\": \"الاشرفيه\",\n        \"DescriptionEnglish\": \"AL ASHRAFEA\",\n        \"Description\": \"الاشرفيه\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-01-11T10:50:38.384Z\",\n        \"createdDate\": \"2018-09-05T19:26:56.335Z\"\n    },\n    {\n        \"Code\": \"008\",\n        \"HasEmployee\": false,\n        \"HasManager\": false,\n        \"DepartmentType\": \"CSPD_Office\",\n        \"MainOfficeInd\": false,\n        \"PrintingInd\": true,\n        \"AddressDetails\": \"الجيزه   تلفون 08560138\",\n        \"AdditionalServiceFees\": 0,\n        \"ArabicIssuanceAuthority\": \"الجيزه\",\n        \"EnglishIssuanceAuthority\": \"AL JEZA\",\n        \"PrintingExport\": \"1\",\n        \"DepartmentTypeExport\": \"1\",\n        \"EmbassyCode\": \"008\",\n        \"OnlineInd\": true,\n        \"CivilOfficeInd\": true,\n        \"InternalOffice\": true,\n        \"PrintingButton\": \"Printing\",\n        \"PassportFileInd\": true,\n        \"CheckIPAddress\": false,\n        \"embassyInd\": false,\n        \"DescriptionArabic\": \"الجيزه\",\n        \"DescriptionEnglish\": \"AL JEZA\",\n        \"Description\": \"الجيزه\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-12-27T16:23:41.158Z\",\n        \"createdDate\": \"2018-09-05T19:26:56.336Z\"\n    },\n    {\n        \"Code\": \"904\",\n        \"HasEmployee\": false,\n        \"HasManager\": false,\n        \"DepartmentType\": \"CSPD_Office\",\n        \"MainOfficeInd\": false,\n        \"PrintingInd\": false,\n        \"AddressDetails\": \"العقبه    تلفون 03313864\",\n        \"AdditionalServiceFees\": 0,\n        \"ArabicIssuanceAuthority\": \"العقبه\",\n        \"EnglishIssuanceAuthority\": \"AQABA\",\n        \"PrintingExport\": \"1\",\n        \"DepartmentTypeExport\": \"1\",\n        \"EmbassyCode\": \"904\",\n        \"OnlineInd\": false,\n        \"CivilOfficeInd\": true,\n        \"InternalOffice\": false,\n        \"PrintingButton\": \"Printing\",\n        \"PassportFileInd\": false,\n        \"CheckIPAddress\": false,\n        \"embassyInd\": false,\n        \"DescriptionArabic\": \"غزة / العقبة\",\n        \"DescriptionEnglish\": \" AQABA\",\n        \"Description\": \"غزة / العقبة\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-02-17T14:45:38.004Z\",\n        \"createdDate\": \"2018-09-05T19:26:56.336Z\"\n    },\n    {\n        \"Code\": \"079\",\n        \"HasEmployee\": false,\n        \"HasManager\": false,\n        \"DepartmentType\": \"CSPD_Office\",\n        \"MainOfficeInd\": false,\n        \"PrintingInd\": true,\n        \"AddressDetails\": \"خلدا ام السماق تلاع العلي\",\n        \"AdditionalServiceFees\": 0,\n        \"ArabicIssuanceAuthority\": \"تلاع العلي\",\n        \"EnglishIssuanceAuthority\": \"TILA ALALI\",\n        \"PrintingExport\": \"1\",\n        \"DepartmentTypeExport\": \"1\",\n        \"EmbassyCode\": \"079\",\n        \"OnlineInd\": false,\n        \"CivilOfficeInd\": true,\n        \"InternalOffice\": false,\n        \"PrintingButton\": \"Printing\",\n        \"PassportFileInd\": false,\n        \"CheckIPAddress\": false,\n        \"embassyInd\": false,\n        \"DescriptionArabic\": \"تلاع العلي\",\n        \"DescriptionEnglish\": \"TILA ALALI\",\n        \"Description\": \"تلاع العلي\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-12-20T08:14:55.581Z\",\n        \"createdDate\": \"2018-09-05T19:26:56.337Z\"\n    },\n    {\n        \"Code\": \"018\",\n        \"HasEmployee\": false,\n        \"HasManager\": false,\n        \"DepartmentType\": \"CSPD_Office\",\n        \"MainOfficeInd\": true,\n        \"PrintingInd\": true,\n        \"AddressDetails\": \"طبربور\",\n        \"AdditionalServiceFees\": 0,\n        \"ArabicIssuanceAuthority\": \"عمان المركز\",\n        \"EnglishIssuanceAuthority\": \"AMMAN CENTER\",\n        \"PrintingExport\": \"1\",\n        \"DepartmentTypeExport\": \"1\",\n        \"EmbassyCode\": \"018\",\n        \"OnlineInd\": false,\n        \"CivilOfficeInd\": true,\n        \"InternalOffice\": false,\n        \"PrintingButton\": \"ViewAndPrinting\",\n        \"PassportFileInd\": true,\n        \"CheckIPAddress\": false,\n        \"embassyInd\": false,\n        \"DescriptionArabic\": \"عمان المركز\",\n        \"DescriptionEnglish\": \"AMMAN CENTER\",\n        \"Description\": \"عمان المركز\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-02-17T13:14:35.735Z\",\n        \"createdDate\": \"2018-09-05T19:26:56.343Z\"\n    },\n    {\n        \"Code\": \"091\",\n        \"HasEmployee\": false,\n        \"HasManager\": false,\n        \"DepartmentType\": \"CSPD_Office\",\n        \"MainOfficeInd\": false,\n        \"PrintingInd\": false,\n        \"AddressDetails\": \"قصر العدل\",\n        \"AdditionalServiceFees\": 0,\n        \"ArabicIssuanceAuthority\": \"عمان\",\n        \"EnglishIssuanceAuthority\": \"amman\",\n        \"PrintingExport\": \"0\",\n        \"DepartmentTypeExport\": \"1\",\n        \"OnlineInd\": false,\n        \"CivilOfficeInd\": true,\n        \"InternalOffice\": false,\n        \"PrintingButton\": \"ViewAndPrinting\",\n        \"PassportFileInd\": false,\n        \"CheckIPAddress\": false,\n        \"embassyInd\": false,\n        \"DescriptionArabic\": \"محطة قصر العدل\",\n        \"DescriptionEnglish\": \"amman\",\n        \"Description\": \"محطة قصر العدل\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-08-09T07:45:05.107Z\",\n        \"createdDate\": \"2020-08-09T07:42:06.054Z\"\n    },\n    {\n        \"Code\": \"069\",\n        \"HasEmployee\": false,\n        \"HasManager\": false,\n        \"DepartmentType\": \"CSPD_Office\",\n        \"MainOfficeInd\": false,\n        \"PrintingInd\": true,\n        \"AddressDetails\": \"حي نزال مقابل حلويات العنبتاوي\",\n        \"AdditionalServiceFees\": 0,\n        \"ArabicIssuanceAuthority\": \"عمان\",\n        \"EnglishIssuanceAuthority\": \"amman\",\n        \"PrintingExport\": \"1\",\n        \"DepartmentTypeExport\": \"1\",\n        \"OnlineInd\": false,\n        \"CivilOfficeInd\": true,\n        \"InternalOffice\": true,\n        \"PrintingButton\": \"ViewAndPrinting\",\n        \"PassportFileInd\": true,\n        \"CheckIPAddress\": false,\n        \"embassyInd\": false,\n        \"DescriptionArabic\": \"حي نزال \",\n        \"DescriptionEnglish\": \"hai nzaal \",\n        \"Description\": \"حي نزال \",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-06-20T08:58:59.084Z\",\n        \"createdDate\": \"2021-06-20T08:55:46.585Z\"\n    }\n]"
				}
			]
		},
		{
			"name": "Get List Of Countries",
			"request": {
				"method": "POST",
				"header": [],
				"url": {
					"raw": "https://10.0.52.241/birthcertificate/countries",
					"protocol": "https",
					"host": [
						"10",
						"0",
						"52",
						"241"
					],
					"path": [
						"birthcertificate",
						"countries"
					]
				},
				"description": "API endpoint to **Get list of Countries** in the system .\n\n> A Successful API Request Will result in a **HTTP 200** status code ."
			},
			"response": [
				{
					"name": "Get List Of Countries",
					"originalRequest": {
						"method": "POST",
						"header": [],
						"url": {
							"raw": "https://10.0.52.241/birthcertificate/countries",
							"protocol": "https",
							"host": [
								"10",
								"0",
								"52",
								"241"
							],
							"path": [
								"birthcertificate",
								"countries"
							]
						}
					},
					"status": "OK",
					"code": 200,
					"_postman_previewlanguage": "json",
					"header": [
						{
							"key": "Date",
							"value": "Sun, 27 Mar 2022 08:00:39 GMT"
						},
						{
							"key": "Server",
							"value": "Apache/2.4.28 (Win64) OpenSSL/1.1.0f"
						},
						{
							"key": "X-Frame-Options",
							"value": "SAMEORIGIN"
						},
						{
							"key": "Cache-Control",
							"value": "no-store"
						},
						{
							"key": "Content-Type",
							"value": "application/json;charset=utf-8"
						},
						{
							"key": "Keep-Alive",
							"value": "timeout=5, max=100"
						},
						{
							"key": "Connection",
							"value": "Keep-Alive"
						},
						{
							"key": "Transfer-Encoding",
							"value": "chunked"
						},
						{
							"key": "Set-Cookie",
							"value": "COOKI3=ffffffff09082ae145525d5f4f58455e445a4a42378b;expires=Sun, 27-Mar-2022 08:02:40 GMT;path=/;secure;httponly"
						}
					],
					"cookie": [],
					"body": "[\n    {\n        \"ISO_Code\": \"675\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"يورو\",\n        \"CurrencyValue\": 2.25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:45:29.492Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"قبرصية\",\n        \"NationalityEnu\": \"CYPRIOTE\",\n        \"DescriptionArabic\": \"قبرص\",\n        \"DescriptionEnglish\": \"Cyprus\",\n        \"Description\": \"قبرص\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:45:29.492Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.228Z\"\n    },\n    {\n        \"ISO_Code\": \"508\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"انغولية\",\n        \"NationalityEnu\": \"ANGOLIAN\",\n        \"DescriptionArabic\": \"انغولا\",\n        \"DescriptionEnglish\": \"Angola\",\n        \"Description\": \"انغولا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-11-28T09:50:37.922Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"729\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"يوهتان\",\n        \"NationalityEnu\": \"BHUTAN\",\n        \"DescriptionArabic\": \"بوهتان\",\n        \"DescriptionEnglish\": \"Bhutan\",\n        \"Description\": \"بوهتان\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-12-11T08:04:12.261Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"540\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"جزر سانت هيلانة\",\n        \"NationalityEnu\": \"SAINT HELENIAN\",\n        \"DescriptionArabic\": \"جزر سانت هيلانة\",\n        \"DescriptionEnglish\": \"Saint Helena Islands\",\n        \"Description\": \"جزر سانت هيلانة\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-11-28T12:04:33.637Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"652\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"تازخستانيه\",\n        \"NationalityEnu\": \"تازخستانيه\",\n        \"DescriptionArabic\": \"تازخستان\",\n        \"DescriptionEnglish\": \"تازخستان\",\n        \"Description\": \"تازخستان\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-03-08T09:39:58.629Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"830\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"هايتيه\",\n        \"NationalityEnu\": \"HAITIAN\",\n        \"DescriptionArabic\": \"هايتي\",\n        \"DescriptionEnglish\": \"Haiti\",\n        \"Description\": \"هايتي\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-03-30T13:07:51.532Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"839\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"غرانادا\",\n        \"NationalityEnu\": \"GRENADA\",\n        \"DescriptionArabic\": \"غرانادا\",\n        \"DescriptionEnglish\": \"Grenada\",\n        \"Description\": \"غرانادا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"528\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"بورنجي\",\n        \"NationalityEnu\": \"BURUNDIAN\",\n        \"DescriptionArabic\": \"بورنجي\",\n        \"DescriptionEnglish\": \"Burundi\",\n        \"Description\": \"بورنجي\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"897\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"جزر فيرجن\",\n        \"NationalityEnu\": \"VIRGIN ISLANDS\",\n        \"DescriptionArabic\": \"جزر فيرجن\",\n        \"DescriptionEnglish\": \"Virgin Islands\",\n        \"Description\": \"جزر فيرجن\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"993\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"مينماري\",\n        \"NationalityEnu\": \"MYANMARIAN\",\n        \"DescriptionArabic\": \"ميانمار\",\n        \"DescriptionEnglish\": \"Myanmar\",\n        \"Description\": \"ميانمار\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"322\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": true,\n        \"CurrencyName\": \"ليرة لبنانية\",\n        \"CurrencyValue\": 3500,\n        \"LastCurrencyUpdate\": \"2018-09-18T19:03:25.403Z\",\n        \"PhoneCode\": \"961\",\n        \"RestrictedExport\": \"0\",\n        \"NationalityAra\": \"لبنانية\",\n        \"NationalityEnu\": \"LEBANESE\",\n        \"DescriptionArabic\": \"لبنان\",\n        \"DescriptionEnglish\": \"Lebanon\",\n        \"Description\": \"لبنان\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-03-26T13:40:52.202Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"995\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"اندوراي\",\n        \"NationalityEnu\": \"ANDORRIAN\",\n        \"DescriptionArabic\": \"إمارة اندورا\",\n        \"DescriptionEnglish\": \"PRINCIPALITY OF ANDORRA\",\n        \"Description\": \"إمارة اندورا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-03-26T14:22:56.079Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"600\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"PhoneCode\": \"599\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"كوراساوي\",\n        \"NationalityEnu\": \"CURACAOI\",\n        \"DescriptionArabic\": \"كوراساو\",\n        \"DescriptionEnglish\": \"CURACAO\",\n        \"Description\": \"كوراساو\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-12-12T08:33:35.977Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"907\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"استونيا\",\n        \"NationalityEnu\": \"ESTONIAN\",\n        \"DescriptionArabic\": \"استونيا\",\n        \"DescriptionEnglish\": \"estonia\",\n        \"Description\": \"استونيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-02-19T14:44:35.540Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"852\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"باليز\",\n        \"NationalityEnu\": \"BELIZE\",\n        \"DescriptionArabic\": \"باليز\",\n        \"DescriptionEnglish\": \"Belize\",\n        \"Description\": \"باليز\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-03-24T11:35:54.782Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"736\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"دولار سنغافوري\",\n        \"CurrencyValue\": 3.5,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:46:49.868Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"سنغافورية\",\n        \"NationalityEnu\": \"SINGAPORE\",\n        \"DescriptionArabic\": \"سنغافورة\",\n        \"DescriptionEnglish\": \"Singapore\",\n        \"Description\": \"سنغافورة\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:46:49.868Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"672\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"كوسوفو\",\n        \"NationalityEnu\": \"KOSOVO\",\n        \"DescriptionArabic\": \"كوسوفو\",\n        \"DescriptionEnglish\": \"kosovo\",\n        \"Description\": \"كوسوفو\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"692\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"البانية\",\n        \"NationalityEnu\": \"ALBANIAN\",\n        \"DescriptionArabic\": \"البانيا\",\n        \"DescriptionEnglish\": \"Albania\",\n        \"Description\": \"البانيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-01-18T14:34:24.318Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"800\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"دولار أمريكي\",\n        \"CurrencyValue\": 2.25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:45:05.629Z\",\n        \"PhoneCode\": \"1\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"امريكيه\",\n        \"NationalityEnu\": \"AMERICAN\",\n        \"DescriptionArabic\": \"امريكا\",\n        \"DescriptionEnglish\": \"USA\",\n        \"Description\": \"امريكا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-05-27T08:42:19.526Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"644\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"سويدية\",\n        \"NationalityEnu\": \"SWEDISH\",\n        \"DescriptionArabic\": \"السويد\",\n        \"DescriptionEnglish\": \"Sweden\",\n        \"Description\": \"السويد\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"762\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"باباء\",\n        \"NationalityEnu\": \"باباء\",\n        \"DescriptionArabic\": \"باباء\",\n        \"DescriptionEnglish\": \"باباء\",\n        \"Description\": \"باباء\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"846\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"سانت لويسا\",\n        \"NationalityEnu\": \"SAINT LUCIA\",\n        \"DescriptionArabic\": \"سانت لوسيا\",\n        \"DescriptionEnglish\": \"Saint Lucia\",\n        \"Description\": \"سانت لوسيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"532\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"ملاوية\",\n        \"NationalityEnu\": \"MALAWIAN\",\n        \"DescriptionArabic\": \"ملاوي\",\n        \"DescriptionEnglish\": \"Malawi\",\n        \"Description\": \"ملاوي\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"715\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"روبية باكستانية\",\n        \"CurrencyValue\": 320,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:24:31.522Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"باكستانية\",\n        \"NationalityEnu\": \"PAKISTANI\",\n        \"DescriptionArabic\": \"باكستان\",\n        \"DescriptionEnglish\": \"Pakistan\",\n        \"Description\": \"باكستان\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-02-18T12:29:35.833Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"853\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"فيجيه\",\n        \"NationalityEnu\": \"FIJIAN\",\n        \"DescriptionArabic\": \"جزر فيجي\",\n        \"DescriptionEnglish\": \"Fiji Island\",\n        \"Description\": \"جزر فيجي\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"733\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"نيبالية\",\n        \"NationalityEnu\": \"NEPALESE\",\n        \"DescriptionArabic\": \"نيبال\",\n        \"DescriptionEnglish\": \"Nepal\",\n        \"Description\": \"نيبال\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-12-17T11:03:39.100Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"665\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"يورو\",\n        \"CurrencyValue\": 2.25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:19:44.308Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"يونانية\",\n        \"NationalityEnu\": \"GREEK\",\n        \"DescriptionArabic\": \"اليونان\",\n        \"DescriptionEnglish\": \"Greece\",\n        \"Description\": \"اليونان\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:19:44.308Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"642\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"PhoneCode\": \"45\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"دنماركية\",\n        \"NationalityEnu\": \"DANISH\",\n        \"DescriptionArabic\": \"الدنمارك\",\n        \"DescriptionEnglish\": \"Denmark\",\n        \"Description\": \"الدنمارك\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-11-28T08:52:27.275Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"511\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"بر أثيوبي\",\n        \"CurrencyValue\": 65,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:46:21.373Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"اثيوبية\",\n        \"NationalityEnu\": \"ETHIOPIAN\",\n        \"DescriptionArabic\": \"اثيوبيا\",\n        \"DescriptionEnglish\": \"Ethiopia\",\n        \"Description\": \"اثيوبيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:46:21.373Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"774\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"هبريديز\",\n        \"NationalityEnu\": \"HEBRIDES\",\n        \"DescriptionArabic\": \"هبريديز\",\n        \"DescriptionEnglish\": \"Hebrides\",\n        \"Description\": \"هبريديز\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"502\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"تشادية\",\n        \"NationalityEnu\": \"CHADI\",\n        \"DescriptionArabic\": \"تشاد\",\n        \"DescriptionEnglish\": \"Chad\",\n        \"Description\": \"تشاد\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"645\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"كرونا نرويجية\",\n        \"CurrencyValue\": 20,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:46:02.719Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"نرويجية\",\n        \"NationalityEnu\": \"NORWEGIAN\",\n        \"DescriptionArabic\": \"النرويج\",\n        \"DescriptionEnglish\": \"Norway\",\n        \"Description\": \"النرويج\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:46:02.719Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"653\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"ترفيزستانيه\",\n        \"NationalityEnu\": \"ترفيزستانيه\",\n        \"DescriptionArabic\": \"ترفيزستان\",\n        \"DescriptionEnglish\": \"ترفيزستان\",\n        \"Description\": \"ترفيزستان\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"842\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"سونت سيرات\",\n        \"NationalityEnu\": \"سونت سيرات\",\n        \"DescriptionArabic\": \"سونت سيرات\",\n        \"DescriptionEnglish\": \"سونت سيرات\",\n        \"Description\": \"سونت سيرات\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"342\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"درهم مغربي\",\n        \"CurrencyValue\": 25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:37:29.928Z\",\n        \"PhoneCode\": \"212\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"مغربية\",\n        \"NationalityEnu\": \"MOROCCAN\",\n        \"DescriptionArabic\": \"المغرب\",\n        \"DescriptionEnglish\": \"Morocco\",\n        \"Description\": \"المغرب\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:37:29.928Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"885\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"باراغواي\",\n        \"NationalityEnu\": \"PARAGUAYAN\",\n        \"DescriptionArabic\": \"باراغواي\",\n        \"DescriptionEnglish\": \"Baraguay\",\n        \"Description\": \"باراغواي\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"513\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"ساحل العاج\",\n        \"NationalityEnu\": \"IVORIAN\",\n        \"DescriptionArabic\": \"ساحل العاج\",\n        \"DescriptionEnglish\": \"Ivory Coast\",\n        \"Description\": \"ساحل العاج\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"724\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"كوريا الشمالية\",\n        \"NationalityEnu\": \"KOREAN\",\n        \"DescriptionArabic\": \"كوريا الشمالية\",\n        \"DescriptionEnglish\": \"North Korea\",\n        \"Description\": \"كوريا الشمالية\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"728\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"كمبودية\",\n        \"NationalityEnu\": \"CAMBODIAN\",\n        \"DescriptionArabic\": \"كمبوديا\",\n        \"DescriptionEnglish\": \"Cambodia\",\n        \"Description\": \"كمبوديا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"996\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"مدغشقر\",\n        \"NationalityEnu\": \"MADAGASCAR\",\n        \"DescriptionArabic\": \"مدغشقر\",\n        \"DescriptionEnglish\": \"Rep. of  Madagascar\",\n        \"Description\": \"مدغشقر\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"827\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"الدومينكانيه\",\n        \"NationalityEnu\": \"DOMINICAN\",\n        \"DescriptionArabic\": \"الدومينكان\",\n        \"DescriptionEnglish\": \"Dominican\",\n        \"Description\": \"الدومينكان\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-12-12T08:33:35.962Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"888\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"غايانا الفرنسيه\",\n        \"NationalityEnu\": \"GUIANIAN\",\n        \"DescriptionArabic\": \"غايانا الفرنسيه\",\n        \"DescriptionEnglish\": \"French Guiana\",\n        \"Description\": \"غايانا الفرنسيه\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"655\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"سوفيتية\",\n        \"NationalityEnu\": \"SOVIET\",\n        \"DescriptionArabic\": \"الاتحاد السوفيتي\",\n        \"DescriptionEnglish\": \"Soviet\",\n        \"Description\": \"الاتحاد السوفيتي\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-03-17T19:33:47.114Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"893\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"بروني\",\n        \"NationalityEnu\": \"BRUNEI\",\n        \"DescriptionArabic\": \"بروني\",\n        \"DescriptionEnglish\": \"Brunei\",\n        \"Description\": \"بروني\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"832\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"جمايكا\",\n        \"NationalityEnu\": \"JAMAICAN\",\n        \"DescriptionArabic\": \"جمايكا\",\n        \"DescriptionEnglish\": \"Jamaica\",\n        \"Description\": \"جمايكا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"702\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"غينيا الجديده\",\n        \"NationalityEnu\": \"GUINEAN\",\n        \"DescriptionArabic\": \"غينيا الجديده\",\n        \"DescriptionEnglish\": \"New Guinea\",\n        \"Description\": \"غينيا الجديده\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"722\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"تايوانيه\",\n        \"NationalityEnu\": \"TAIWANESE\",\n        \"DescriptionArabic\": \"تايوان\",\n        \"DescriptionEnglish\": \"Taiwan\",\n        \"Description\": \"تايوان\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"666\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"صربيه\",\n        \"NationalityEnu\": \"SERBIA\",\n        \"DescriptionArabic\": \"صربيا\",\n        \"DescriptionEnglish\": \"SERBIA\",\n        \"Description\": \"صربيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"828\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"سلفادوريه\",\n        \"NationalityEnu\": \"SALVADOR\",\n        \"DescriptionArabic\": \"السلفادور\",\n        \"DescriptionEnglish\": \"Salvador\",\n        \"Description\": \"السلفادور\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-12-12T13:41:37.833Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"527\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"بوتسوانية\",\n        \"NationalityEnu\": \"BOTSWANAN\",\n        \"DescriptionArabic\": \"بوتسوانا\",\n        \"DescriptionEnglish\": \"Botswana\",\n        \"Description\": \"بوتسوانا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"734\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"ين ياباني\",\n        \"CurrencyValue\": 260,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:39:55.170Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"يابانية\",\n        \"NationalityEnu\": \"JAPANESE\",\n        \"DescriptionArabic\": \"اليابان\",\n        \"DescriptionEnglish\": \"Japan\",\n        \"Description\": \"اليابان\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:39:55.170Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"771\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"نورو\",\n        \"NationalityEnu\": \"نورو\",\n        \"DescriptionArabic\": \"نورو\",\n        \"DescriptionEnglish\": \"نورو\",\n        \"Description\": \"نورو\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"908\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"رواندي\",\n        \"NationalityEnu\": \"RWANDA\",\n        \"DescriptionArabic\": \"جمهورية رواندا\",\n        \"DescriptionEnglish\": \"Republic of Rwanda\",\n        \"Description\": \"جمهورية رواندا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"721\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"يوان صيني\",\n        \"CurrencyValue\": 20,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:34:07.210Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"الصين الشعبية\",\n        \"NationalityEnu\": \"CHINESE\",\n        \"DescriptionArabic\": \"الصين الشعبية\",\n        \"DescriptionEnglish\": \"China\",\n        \"Description\": \"الصين الشعبية\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-05-28T12:07:39.165Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"826\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"كوستاريكيه\",\n        \"NationalityEnu\": \"COSTARICAN\",\n        \"DescriptionArabic\": \"كوستاريكا\",\n        \"DescriptionEnglish\": \"Costarica\",\n        \"Description\": \"كوستاريكا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"343\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"PhoneCode\": \"222\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"موريتانية\",\n        \"NationalityEnu\": \"MAURITANIAN\",\n        \"DescriptionArabic\": \"موريتانيا\",\n        \"DescriptionEnglish\": \"Mauritania\",\n        \"Description\": \"موريتانيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"990\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"سلوفيني\",\n        \"NationalityEnu\": \"SLOVENIA\",\n        \"DescriptionArabic\": \"سلوفينيا\",\n        \"DescriptionEnglish\": \"slovenia\",\n        \"Description\": \"سلوفينيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"680\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"تشكوسلوفاكية\",\n        \"NationalityEnu\": \"CZECHOSLOVAKIAN\",\n        \"DescriptionArabic\": \"تشيكوسلوفاكيا\",\n        \"DescriptionEnglish\": \"Czechoslovakia\",\n        \"Description\": \"تشيكوسلوفاكيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"737\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"مالديفية\",\n        \"NationalityEnu\": \"MALDIVES\",\n        \"DescriptionArabic\": \"مالديف\",\n        \"DescriptionEnglish\": \"Maldives\",\n        \"Description\": \"مالديف\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"731\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"فيتنامية\",\n        \"NationalityEnu\": \"VIETNAMESE\",\n        \"DescriptionArabic\": \"فيتنام\",\n        \"DescriptionEnglish\": \"Vietnam\",\n        \"Description\": \"فيتنام\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"316\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"ريال عماني\",\n        \"CurrencyValue\": 1,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:43:06.406Z\",\n        \"PhoneCode\": \"968\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"عمانية\",\n        \"NationalityEnu\": \"OMANI\",\n        \"DescriptionArabic\": \"سلطنة عمان\",\n        \"DescriptionEnglish\": \"Oman\",\n        \"Description\": \"سلطنة عمان\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-06-15T09:26:25.965Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"825\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"باربيدوسيه\",\n        \"NationalityEnu\": \"BARBADOS\",\n        \"DescriptionArabic\": \"باربيدوس\",\n        \"DescriptionEnglish\": \"Barbados\",\n        \"Description\": \"باربيدوس\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"831\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"هندوراسيه\",\n        \"NationalityEnu\": \"HONDURASIA\",\n        \"DescriptionArabic\": \"هندوراس\",\n        \"DescriptionEnglish\": \"Honduras\",\n        \"Description\": \"هندوراس\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"514\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"زامبيا\",\n        \"NationalityEnu\": \"ZAMBIAN\",\n        \"DescriptionArabic\": \"زامبيا\",\n        \"DescriptionEnglish\": \"Zambia\",\n        \"Description\": \"زامبيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"312\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"دينار كويتي\",\n        \"CurrencyValue\": 0.7,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:41:11.961Z\",\n        \"PhoneCode\": \"965\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"كويتية\",\n        \"NationalityEnu\": \"KUWAIT\",\n        \"DescriptionArabic\": \"الكويت\",\n        \"DescriptionEnglish\": \"Kuwait\",\n        \"Description\": \"الكويت\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-11-25T08:44:44.266Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"670\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"يوغسلافية\",\n        \"NationalityEnu\": \"YUGOSLAVIAN\",\n        \"DescriptionArabic\": \"يوغسلافيا\",\n        \"DescriptionEnglish\": \"Yugoslavia\",\n        \"Description\": \"يوغسلافيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"636\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"PhoneCode\": \"378\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"سان ريمو\",\n        \"NationalityEnu\": \"SAN MARINO\",\n        \"DescriptionArabic\": \"سان مارينو\",\n        \"DescriptionEnglish\": \"San Marino\",\n        \"Description\": \"سان مارينو\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"523\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"مالاغاسي\",\n        \"NationalityEnu\": \"MALAGASY\",\n        \"DescriptionArabic\": \"مالاغاسي\",\n        \"DescriptionEnglish\": \"Malagasy\",\n        \"Description\": \"مالاغاسي\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"542\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"جزر ساوتومي\",\n        \"NationalityEnu\": \"SAOTOMEAN\",\n        \"DescriptionArabic\": \"جزر ساوتومي\",\n        \"DescriptionEnglish\": \"Sao Tome and Pricipe\",\n        \"Description\": \"جزر ساوتومي\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"535\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"جزر القمر\",\n        \"NationalityEnu\": \"COMORAN\",\n        \"DescriptionArabic\": \"جزر القمر\",\n        \"DescriptionEnglish\": \"Comoro Islands\",\n        \"Description\": \"جزر القمر\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"730\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"تيلندية\",\n        \"NationalityEnu\": \"THAI\",\n        \"DescriptionArabic\": \"تايلند\",\n        \"DescriptionEnglish\": \"Thailand\",\n        \"Description\": \"تايلند\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"310\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"ريال سعودي\",\n        \"CurrencyValue\": 9,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:35:46.312Z\",\n        \"PhoneCode\": \"966\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"سعودي\",\n        \"NationalityEnu\": \"SAUDIAN\",\n        \"DescriptionArabic\": \"السعودية\",\n        \"DescriptionEnglish\": \"Saudia Arabia\",\n        \"Description\": \"السعودية\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-02-17T13:14:33.954Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"883\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"بوليفيه\",\n        \"NationalityEnu\": \"BOLIVIAN\",\n        \"DescriptionArabic\": \"بوليفيا\",\n        \"DescriptionEnglish\": \"Bolivia\",\n        \"Description\": \"بوليفيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"321\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": true,\n        \"CurrencyName\": \"ليرة سورية\",\n        \"CurrencyValue\": 1200,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:36:41.711Z\",\n        \"PhoneCode\": \"963\",\n        \"RestrictedExport\": \"0\",\n        \"NationalityAra\": \"سورية\",\n        \"NationalityEnu\": \"SYRIAN\",\n        \"DescriptionArabic\": \"سوريا\",\n        \"DescriptionEnglish\": \"Syria\",\n        \"Description\": \"سوريا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:36:41.711Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"516\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"سنغالية\",\n        \"NationalityEnu\": \"SENEGALESE\",\n        \"DescriptionArabic\": \"السنغال\",\n        \"DescriptionEnglish\": \"Sengal\",\n        \"Description\": \"السنغال\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"778\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"ج توكلو\",\n        \"NationalityEnu\": \"ج توكلو\",\n        \"DescriptionArabic\": \"ج توكلو\",\n        \"DescriptionEnglish\": \"ج توكلو\",\n        \"Description\": \"ج توكلو\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"848\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"تركس وكايكس\",\n        \"NationalityEnu\": \"TURKS AND CAICOS\",\n        \"DescriptionArabic\": \"تركس وكايكس\",\n        \"DescriptionEnglish\": \"Turks and Caicos\",\n        \"Description\": \"تركس وكايكس\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"650\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"يورو\",\n        \"CurrencyValue\": 2.25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:30:11.407Z\",\n        \"PhoneCode\": \"49\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"المانية\",\n        \"NationalityEnu\": \"GERMAN\",\n        \"DescriptionArabic\": \"المانيا\",\n        \"DescriptionEnglish\": \"Germany\",\n        \"Description\": \"المانيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:30:11.407Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"810\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"دولار كندي\",\n        \"CurrencyValue\": 3.5,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:27:09.769Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"كنديه\",\n        \"NationalityEnu\": \"CANADIAN\",\n        \"DescriptionArabic\": \"كندا\",\n        \"DescriptionEnglish\": \"Canada\",\n        \"Description\": \"كندا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:27:09.769Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"314\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"ريال قطري\",\n        \"CurrencyValue\": 9,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:36:52.226Z\",\n        \"PhoneCode\": \"974\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"قطرية\",\n        \"NationalityEnu\": \"QATARI\",\n        \"DescriptionArabic\": \"قطر\",\n        \"DescriptionEnglish\": \"Qatar\",\n        \"Description\": \"قطر\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-09-20T10:45:13.613Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"651\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"بلاروسيا\",\n        \"NationalityEnu\": \"BELARUS\",\n        \"DescriptionArabic\": \"روسيا البيضاء\",\n        \"DescriptionEnglish\": \"BELARUS\",\n        \"Description\": \"روسيا البيضاء\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"880\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"بيرو\",\n        \"NationalityEnu\": \"PERUSAL\",\n        \"DescriptionArabic\": \"بيرو\",\n        \"DescriptionEnglish\": \"Peru\",\n        \"Description\": \"بيرو\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"667\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"ليتوانية\",\n        \"NationalityEnu\": \"LITHUANIAN\",\n        \"DescriptionArabic\": \"ليتوانيا\",\n        \"DescriptionEnglish\": \"Lithuania\",\n        \"Description\": \"ليتوانيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"525\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"فلبينية\",\n        \"NationalityEnu\": \"PHILIPPINO\",\n        \"DescriptionArabic\": \"الفلبين\",\n        \"DescriptionEnglish\": \"Philippines\",\n        \"Description\": \"الفلبين\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"884\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"اوروغواي\",\n        \"NationalityEnu\": \"URUGUAYAN\",\n        \"DescriptionArabic\": \"اوروغواي\",\n        \"DescriptionEnglish\": \"Uruguay\",\n        \"Description\": \"اوروغواي\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"350\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"جنيه سوداني\",\n        \"CurrencyValue\": 110,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:36:19.881Z\",\n        \"PhoneCode\": \"249\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"سودانية\",\n        \"NationalityEnu\": \"SUDANESE\",\n        \"DescriptionArabic\": \"السودان\",\n        \"DescriptionEnglish\": \"Sudan\",\n        \"Description\": \"السودان\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:36:19.881Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"524\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"فلتا العليا\",\n        \"NationalityEnu\": \"BURKINABE\",\n        \"DescriptionArabic\": \"فلتا العليا\",\n        \"DescriptionEnglish\": \"Upper Volta\",\n        \"Description\": \"فلتا العليا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"001\",\n        \"CountryGroup\": \"Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"دينار اردني\",\n        \"PhoneCode\": \"962\",\n        \"RestrictedExport\": \"1\",\n        \"CurrencyNameEnu\": \"JOD\",\n        \"NationalityAra\": \"اردني\",\n        \"NationalityEnu\": \"JORDANIAN\",\n        \"DescriptionArabic\": \"الاردن\",\n        \"DescriptionEnglish\": \"JORDAN\",\n        \"Description\": \"الاردن\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-03-21T09:23:20.749Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"763\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"جوسولومون\",\n        \"NationalityEnu\": \"SOLOMON ISLAND\",\n        \"DescriptionArabic\": \"جزر سولومون\",\n        \"DescriptionEnglish\": \"Solomon Island\",\n        \"Description\": \"جزر سولومون\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"503\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"مالية\",\n        \"NationalityEnu\": \"MALIAN\",\n        \"DescriptionArabic\": \"مالي\",\n        \"DescriptionEnglish\": \"Mali\",\n        \"Description\": \"مالي\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"887\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"فولكلاند\",\n        \"NationalityEnu\": \"FAULKLAND\",\n        \"DescriptionArabic\": \"فولكلاند\",\n        \"DescriptionEnglish\": \"Faulkland\",\n        \"Description\": \"فولكلاند\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"719\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"رينجيت ماليزي\",\n        \"CurrencyValue\": 10,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:40:55.490Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"ماليزية\",\n        \"NationalityEnu\": \"MALAYSIAN\",\n        \"DescriptionArabic\": \"ماليزيا\",\n        \"DescriptionEnglish\": \"Malaysia\",\n        \"Description\": \"ماليزيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:40:55.490Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"352\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"ارترية\",\n        \"NationalityEnu\": \"ARETIRIAN\",\n        \"DescriptionArabic\": \"ارتريا\",\n        \"DescriptionEnglish\": \"Aretiria\",\n        \"Description\": \"ارتريا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-03-16T08:44:36.156Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"648\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"مالطية\",\n        \"NationalityEnu\": \"MALTESE\",\n        \"DescriptionArabic\": \"مالطا\",\n        \"DescriptionEnglish\": \"Malta\",\n        \"Description\": \"مالطا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"112\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"PhoneCode\": \"220\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"جامبي\",\n        \"NationalityEnu\": \"GAMBIAN\",\n        \"DescriptionArabic\": \"جامبيا\",\n        \"DescriptionEnglish\": \"GAMBIA\",\n        \"Description\": \"جامبيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"898\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"سنتالوسيا\",\n        \"NationalityEnu\": \"SAINTLUCIA\",\n        \"DescriptionArabic\": \"سنتالوسيا\",\n        \"DescriptionEnglish\": \"Saintlucia\",\n        \"Description\": \"سنتالوسيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"699\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"كرواتي\",\n        \"NationalityEnu\": \"CORATIAN\",\n        \"DescriptionArabic\": \"كرواتيا\",\n        \"DescriptionEnglish\": \"Croatia\",\n        \"Description\": \"كرواتيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"773\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"غينيه\",\n        \"NationalityEnu\": \"GUINEAN\",\n        \"DescriptionArabic\": \"غينيه\",\n        \"DescriptionEnglish\": \"Guinea\",\n        \"Description\": \"غينيه\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"890\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"بوسنيه\",\n        \"NationalityEnu\": \"BOSNIAN HERZOGEVINIAN\",\n        \"DescriptionArabic\": \"البوسنه والهرسك\",\n        \"DescriptionEnglish\": \"Bosnia and Herzegovina\",\n        \"Description\": \"البوسنه والهرسك\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"506\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"يوغندية\",\n        \"NationalityEnu\": \"UGANDANN\",\n        \"DescriptionArabic\": \"يوغندا\",\n        \"DescriptionEnglish\": \"Uganda\",\n        \"Description\": \"يوغندا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"835\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"البهاما\",\n        \"NationalityEnu\": \"BAHAMAS\",\n        \"DescriptionArabic\": \"البهاما\",\n        \"DescriptionEnglish\": \"Bahamas\",\n        \"Description\": \"البهاما\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-12-27T16:09:44.268Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"717\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"ريال إيراني\",\n        \"CurrencyValue\": 95000,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:39:41.240Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"ايرانية\",\n        \"NationalityEnu\": \"IRANIAN\",\n        \"DescriptionArabic\": \"ايران\",\n        \"DescriptionEnglish\": \"Iran\",\n        \"Description\": \"ايران\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-05-30T07:07:10.801Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"992\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"لينششتانيه\",\n        \"NationalityEnu\": \"LEICHTENSTEINIAN\",\n        \"DescriptionArabic\": \"لينششتاين\",\n        \"DescriptionEnglish\": \"leichtenstein\",\n        \"Description\": \"لينششتاين\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"889\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"اوكراني\",\n        \"NationalityEnu\": \"UKRAINIAN\",\n        \"DescriptionArabic\": \"اوكرانيا\",\n        \"DescriptionEnglish\": \"Ukraine\",\n        \"Description\": \"اوكرانيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"537\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"ناميبية\",\n        \"NationalityEnu\": \"NAMIBIAN\",\n        \"DescriptionArabic\": \"ناميبيا\",\n        \"DescriptionEnglish\": \"Namibia\",\n        \"Description\": \"ناميبيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"317\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": true,\n        \"CurrencyName\": \"ريال يمني\",\n        \"CurrencyValue\": 600,\n        \"LastCurrencyUpdate\": \"2018-09-18T19:00:16.142Z\",\n        \"PhoneCode\": \"967\",\n        \"RestrictedExport\": \"0\",\n        \"NationalityAra\": \"يمنية\",\n        \"NationalityEnu\": \"YEMENI\",\n        \"DescriptionArabic\": \"اليمن\",\n        \"DescriptionEnglish\": \"Yemen\",\n        \"Description\": \"اليمن\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-18T19:00:16.142Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"881\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"كولومبيه\",\n        \"NationalityEnu\": \"COLOMBIAN\",\n        \"DescriptionArabic\": \"كولومبيا\",\n        \"DescriptionEnglish\": \"Colombia\",\n        \"Description\": \"كولومبيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"663\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"مقدونيه\",\n        \"NationalityEnu\": \"MAKDONIAN\",\n        \"DescriptionArabic\": \"مقدونيا\",\n        \"DescriptionEnglish\": \"Makdonia\",\n        \"Description\": \"مقدونيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"739\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"هونغ كونغ\",\n        \"NationalityEnu\": \"HONG KONG\",\n        \"DescriptionArabic\": \"هونغ كونغ\",\n        \"DescriptionEnglish\": \"Hong Kong\",\n        \"Description\": \"هونغ كونغ\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"768\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"ج جيللبرت\",\n        \"NationalityEnu\": \"ج جيللبرت\",\n        \"DescriptionArabic\": \"ج جيللبرت\",\n        \"DescriptionEnglish\": \"ج جيللبرت\",\n        \"Description\": \"ج جيللبرت\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"991\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"قرغيزيه\",\n        \"NationalityEnu\": \"KYRGYZIAN\",\n        \"DescriptionArabic\": \"جمهورية قرغيز\",\n        \"DescriptionEnglish\": \"Kyrgyz Republic\",\n        \"Description\": \"جمهورية قرغيز\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"994\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"كيرجستانيه\",\n        \"NationalityEnu\": \"KYRGYZSTAN\",\n        \"DescriptionArabic\": \"كيرجستان\",\n        \"DescriptionEnglish\": \"kyrgyzstan\",\n        \"Description\": \"كيرجستان\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"340\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"دينار تونسي\",\n        \"CurrencyValue\": 7,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:34:53.324Z\",\n        \"PhoneCode\": \"216\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"تونسية\",\n        \"NationalityEnu\": \"TUNISIAN\",\n        \"DescriptionArabic\": \"تونس\",\n        \"DescriptionEnglish\": \"Tunisia\",\n        \"Description\": \"تونس\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:34:53.324Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"510\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"زائيرية\",\n        \"NationalityEnu\": \"ZAIRIAN\",\n        \"DescriptionArabic\": \"زائير\",\n        \"DescriptionEnglish\": \"Zaire\",\n        \"Description\": \"زائير\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"776\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"ج الباسفيك\",\n        \"NationalityEnu\": \"ج الباسفيك\",\n        \"DescriptionArabic\": \"ج الباسفيك\",\n        \"DescriptionEnglish\": \"ج الباسفيك\",\n        \"Description\": \"ج الباسفيك\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"531\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"تايلندي\",\n        \"NationalityEnu\": \"TAILAND\",\n        \"DescriptionArabic\": \"تايلند\",\n        \"DescriptionEnglish\": \"TAILAND\",\n        \"Description\": \"تايلند\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"876\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"ريال برازيلي\",\n        \"CurrencyValue\": 4,\n        \"PhoneCode\": \"962\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"ج ويل\",\n        \"NationalityEnu\": \"ج ويل\",\n        \"DescriptionArabic\": \"الالللل\",\n        \"DescriptionEnglish\": \"test\",\n        \"Description\": \"الالللل\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-08-30T07:29:23.137Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"850\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"ريال برازيلي\",\n        \"CurrencyValue\": 9,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:29:54.743Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"برازيليه\",\n        \"NationalityEnu\": \"BRAZILIAN\",\n        \"DescriptionArabic\": \"البرازيل\",\n        \"DescriptionEnglish\": \"Brazil\",\n        \"Description\": \"البرازيل\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:29:54.743Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"683\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"شيكيه\",\n        \"NationalityEnu\": \"CZECH\",\n        \"DescriptionArabic\": \"تشيك\",\n        \"DescriptionEnglish\": \"Czech\",\n        \"Description\": \"تشيك\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"685\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"بولونية\",\n        \"NationalityEnu\": \"POLISH\",\n        \"DescriptionArabic\": \"بولونيا\",\n        \"DescriptionEnglish\": \"Poland\",\n        \"Description\": \"بولونيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"860\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"فنزويليه\",\n        \"NationalityEnu\": \"VENEZUELIAN\",\n        \"DescriptionArabic\": \"فنزويلا\",\n        \"DescriptionEnglish\": \"Venezuela\",\n        \"Description\": \"فنزويلا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"740\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"مكاو\",\n        \"NationalityEnu\": \"MACAU\",\n        \"DescriptionArabic\": \"مكاو\",\n        \"DescriptionEnglish\": \"Macau\",\n        \"Description\": \"مكاو\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"512\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"غانا\",\n        \"NationalityEnu\": \"GHANAIAN\",\n        \"DescriptionArabic\": \"غانا\",\n        \"DescriptionEnglish\": \"Ghana\",\n        \"Description\": \"غانا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"843\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"انتينيل\",\n        \"NationalityEnu\": \"انتينيل\",\n        \"DescriptionArabic\": \"انتينيل\",\n        \"DescriptionEnglish\": \"انتينيل\",\n        \"Description\": \"انتينيل\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"643\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"فرنك سويسري\",\n        \"CurrencyValue\": 3,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:34:17.187Z\",\n        \"PhoneCode\": \"41\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"سويسرية\",\n        \"NationalityEnu\": \"SWISS\",\n        \"DescriptionArabic\": \"سويسرا\",\n        \"DescriptionEnglish\": \"SwitzerLand\",\n        \"Description\": \"سويسرا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:34:17.187Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"820\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"دولار أمريكي\",\n        \"CurrencyValue\": 2.25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:43:16.604Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"مكسيكيه\",\n        \"NationalityEnu\": \"MEXICAN\",\n        \"DescriptionArabic\": \"المكسيك\",\n        \"DescriptionEnglish\": \"Mexico\",\n        \"Description\": \"المكسيك\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:43:16.604Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"662\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"دولار أمريكي\",\n        \"CurrencyValue\": 2.25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:44:10.147Z\",\n        \"PhoneCode\": \"006\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"روسيه\",\n        \"NationalityEnu\": \"RUSSIAN\",\n        \"DescriptionArabic\": \"روسيا\",\n        \"DescriptionEnglish\": \"Russia\",\n        \"Description\": \"روسيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-03-08T12:20:17.710Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"899\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"بنينيه\",\n        \"NationalityEnu\": \"BENIN\",\n        \"DescriptionArabic\": \"بنين\",\n        \"DescriptionEnglish\": \"Benin\",\n        \"Description\": \"بنين\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"701\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"روبية هندية\",\n        \"CurrencyValue\": 160,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:44:25.029Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"هندية\",\n        \"NationalityEnu\": \"INDIAN\",\n        \"DescriptionArabic\": \"الهند\",\n        \"DescriptionEnglish\": \"India\",\n        \"Description\": \"الهند\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:44:25.029Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"718\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"روبية أندونيسية\",\n        \"CurrencyValue\": 33000,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:35:29.299Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"اندونيسية\",\n        \"NationalityEnu\": \"ANDONISIAN\",\n        \"DescriptionArabic\": \"اندونيسا\",\n        \"DescriptionEnglish\": \"Indonesia\",\n        \"Description\": \"اندونيسا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:35:29.299Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"723\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"سيرلنكية\",\n        \"NationalityEnu\": \"SRILANKAN\",\n        \"DescriptionArabic\": \"سيرلانكا\",\n        \"DescriptionEnglish\": \"Sri Lanka\",\n        \"Description\": \"سيرلانكا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"630\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"يورو\",\n        \"CurrencyValue\": 2.25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:37:56.656Z\",\n        \"PhoneCode\": \"39\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"ايطالية\",\n        \"NationalityEnu\": \"ITALIAN\",\n        \"DescriptionArabic\": \"ايطاليا\",\n        \"DescriptionEnglish\": \"Italy\",\n        \"Description\": \"ايطاليا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:37:56.656Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"320\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"دولار أمريكي\",\n        \"CurrencyValue\": 2.25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:23:05.444Z\",\n        \"PhoneCode\": \"964\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"عراقية\",\n        \"NationalityEnu\": \"IRAQI\",\n        \"DescriptionArabic\": \"العراق\",\n        \"DescriptionEnglish\": \"Iraq\",\n        \"Description\": \"العراق\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:23:05.444Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"833\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"سوريناميه\",\n        \"NationalityEnu\": \"SURINAM\",\n        \"DescriptionArabic\": \"سورينام\",\n        \"DescriptionEnglish\": \"Surinam\",\n        \"Description\": \"سورينام\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"741\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"تيمور\",\n        \"NationalityEnu\": \"تيمور\",\n        \"DescriptionArabic\": \"تيمور\",\n        \"DescriptionEnglish\": \"تيمور\",\n        \"Description\": \"تيمور\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"815\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"غرينلندا\",\n        \"NationalityEnu\": \"GREENLANDAR\",\n        \"DescriptionArabic\": \"غرينلندا\",\n        \"DescriptionEnglish\": \"Greenland\",\n        \"Description\": \"غرينلندا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"637\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"موناكو\",\n        \"NationalityEnu\": \"MONACO\",\n        \"DescriptionArabic\": \"موناكو\",\n        \"DescriptionEnglish\": \"Monaco\",\n        \"Description\": \"موناكو\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"313\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"درهم إماراتي\",\n        \"CurrencyValue\": 9,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:36:31.817Z\",\n        \"PhoneCode\": \"971\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"اماراتية\",\n        \"NationalityEnu\": \"EMIRATE\",\n        \"DescriptionArabic\": \"الامارات\",\n        \"DescriptionEnglish\": \"UAE\",\n        \"Description\": \"الامارات\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-03-08T11:09:18.966Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"331\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": true,\n        \"CurrencyName\": \"دينار ليبي\",\n        \"CurrencyValue\": 5,\n        \"LastCurrencyUpdate\": \"2018-09-18T19:02:41.667Z\",\n        \"PhoneCode\": \"218\",\n        \"RestrictedExport\": \"0\",\n        \"NationalityAra\": \"ليبية\",\n        \"NationalityEnu\": \"LIBYAN\",\n        \"DescriptionArabic\": \"ليبيا\",\n        \"DescriptionEnglish\": \"Libya\",\n        \"Description\": \"ليبيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-07-02T12:01:37.385Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"656\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"مانات\",\n        \"CurrencyValue\": 4,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:29:29.840Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"اذربيجانيه\",\n        \"NationalityEnu\": \"AZERBAIJANI\",\n        \"DescriptionArabic\": \"اذربيجان\",\n        \"DescriptionEnglish\": \"Azerbaijan\",\n        \"Description\": \"اذربيجان\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-06-09T07:37:48.502Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"765\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"جفيكيه\",\n        \"NationalityEnu\": \"جفيكيه\",\n        \"DescriptionArabic\": \"جفيكي\",\n        \"DescriptionEnglish\": \"جفيكي\",\n        \"Description\": \"جفيكي\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"896\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"برتغالية\",\n        \"NationalityEnu\": \"PORTUGESE\",\n        \"DescriptionArabic\": \"البرتغال\",\n        \"DescriptionEnglish\": \"Portugal\",\n        \"Description\": \"البرتغال\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-06-27T13:02:47.921Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"891\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"دولار أمريكي\",\n        \"CurrencyValue\": 2.25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:39:25.930Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"اوزبكية\",\n        \"NationalityEnu\": \"UZBEKISTAN\",\n        \"DescriptionArabic\": \"اوزباكستان\",\n        \"DescriptionEnglish\": \"Uzbekistan\",\n        \"Description\": \"اوزباكستان\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-06-09T06:41:48.363Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"732\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"منغولية\",\n        \"NationalityEnu\": \"MANGOLLIAN\",\n        \"DescriptionArabic\": \"منغوليا\",\n        \"DescriptionEnglish\": \"Mangolla\",\n        \"Description\": \"منغوليا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"906\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"راند جنوب أفريقي\",\n        \"CurrencyValue\": 35,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:33:32.990Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"جنوب افريقيه\",\n        \"NationalityEnu\": \"SOUTH AFRICA\",\n        \"DescriptionArabic\": \"جنوب افريقيا\",\n        \"DescriptionEnglish\": \"SOUTH AFRICA\",\n        \"Description\": \"جنوب افريقيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:33:32.990Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"625\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"يورو\",\n        \"CurrencyValue\": 2.25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:29:14.937Z\",\n        \"PhoneCode\": \"33\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"فرنسية\",\n        \"NationalityEnu\": \"FRENCH\",\n        \"DescriptionArabic\": \"فرنسا\",\n        \"DescriptionEnglish\": \"France\",\n        \"Description\": \"فرنسا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:29:14.937Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"529\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"افريقيا الوسطى\",\n        \"NationalityEnu\": \"CENTRAI AFRICA\",\n        \"DescriptionArabic\": \"افريقيا الوسطى\",\n        \"DescriptionEnglish\": \"Central Africa\",\n        \"Description\": \"افريقيا الوسطى\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-03-15T10:52:43.385Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"851\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"غيانا\",\n        \"NationalityEnu\": \"GUYANA\",\n        \"DescriptionArabic\": \"غيانا\",\n        \"DescriptionEnglish\": \"guyana\",\n        \"Description\": \"غيانا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"509\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"زيمبابوية\",\n        \"NationalityEnu\": \"ZIMBABWE\",\n        \"DescriptionArabic\": \"زيمبابويه\",\n        \"DescriptionEnglish\": \"Zimbabwe\",\n        \"Description\": \"زيمبابويه\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"330\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"جنيه مصري\",\n        \"CurrencyValue\": 40,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:40:19.490Z\",\n        \"PhoneCode\": \"962\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"مصرية\",\n        \"NationalityEnu\": \"EGYPTIaaaN\",\n        \"DescriptionArabic\": \"مصر\",\n        \"DescriptionEnglish\": \"Egypt\",\n        \"Description\": \"مصر\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-09-29T07:38:12.658Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"767\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"بولوليزيه\",\n        \"NationalityEnu\": \"بولوليزيه\",\n        \"DescriptionArabic\": \"بولوليزيا\",\n        \"DescriptionEnglish\": \"بولوليزيا\",\n        \"Description\": \"بولوليزيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"902\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"شيشانيه\",\n        \"NationalityEnu\": \"CHECHENIA\",\n        \"DescriptionArabic\": \"جمهورية الشيشان\",\n        \"DescriptionEnglish\": \"Chechian\",\n        \"Description\": \"جمهورية الشيشان\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"355\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"PhoneCode\": \"211\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"جنوب السودان\",\n        \"NationalityEnu\": \"SOUTH SUDAN\",\n        \"DescriptionArabic\": \"جنوب السودان\",\n        \"DescriptionEnglish\": \"South Sudan\",\n        \"Description\": \"جنوب السودان\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"837\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"بيليزيه\",\n        \"NationalityEnu\": \"BELIZEAN\",\n        \"DescriptionArabic\": \"بيليز\",\n        \"DescriptionEnglish\": \"BELIZE\",\n        \"Description\": \"بيليز\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"635\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"يورو\",\n        \"CurrencyValue\": 2.25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:42:54.530Z\",\n        \"PhoneCode\": \"34\",\n        \"RestrictedExport\": \"1\",\n        \"CurrencyNameEnu\": \"euro\",\n        \"NationalityAra\": \"اسبانية\",\n        \"NationalityEnu\": \"SPANISH\",\n        \"DescriptionArabic\": \"اسبانيا\",\n        \"DescriptionEnglish\": \"Spain\",\n        \"Description\": \"اسبانيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-03-14T09:56:10.260Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"886\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"غايافا\",\n        \"NationalityEnu\": \"غايافا\",\n        \"DescriptionArabic\": \"غايافا\",\n        \"DescriptionEnglish\": \"غايافا\",\n        \"Description\": \"غايافا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"003\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"شيكل إسرائيلي\",\n        \"CurrencyValue\": 9,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:37:04.929Z\",\n        \"PhoneCode\": \"970\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"فلسطيني\",\n        \"NationalityEnu\": \"PALESTINIAN 48\",\n        \"DescriptionArabic\": \"فلسطين 48\",\n        \"DescriptionEnglish\": \"Palestine\",\n        \"Description\": \"فلسطين 48\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-03-24T13:39:50.671Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"000\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"شيكل إسرائيلي\",\n        \"CurrencyValue\": 0.126,\n        \"LastCurrencyUpdate\": \"2021-09-14T11:28:29.870Z\",\n        \"PhoneCode\": \"972\",\n        \"RestrictedExport\": \"1\",\n        \"CurrencyNameEnu\": \"\",\n        \"NationalityAra\": \"اسرائيلي\",\n        \"NationalityEnu\": \"ISRAELI\",\n        \"DescriptionArabic\": \"اسرائيل\",\n        \"DescriptionEnglish\": \"Israel\",\n        \"Description\": \"اسرائيل\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-09-14T11:28:29.870Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"903\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"بوسنيه\",\n        \"NationalityEnu\": \"BOSNIAN\",\n        \"DescriptionArabic\": \"البوسنه\",\n        \"DescriptionEnglish\": \"Bosnia\",\n        \"Description\": \"البوسنه\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"905\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"داغستاني\",\n        \"NationalityEnu\": \"DAGHESTANI\",\n        \"DescriptionArabic\": \"داغستان\",\n        \"DescriptionEnglish\": \"Daghestan\",\n        \"Description\": \"داغستان\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"664\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"لاتفيه\",\n        \"NationalityEnu\": \"LATVIAN\",\n        \"DescriptionArabic\": \"لاتفيا\",\n        \"DescriptionEnglish\": \"Latvia\",\n        \"Description\": \"لاتفيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"845\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"سانت كيتس ونيفس\",\n        \"NationalityEnu\": \"SAINT KITTS AND NEVIS\",\n        \"DescriptionArabic\": \"سانت كيتس ونيفس\",\n        \"DescriptionEnglish\": \"Saint Kitts and Nevis\",\n        \"Description\": \"سانت كيتس ونيفس\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"526\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"داهومي\",\n        \"NationalityEnu\": \"DAHOMEY\",\n        \"DescriptionArabic\": \"داهومي\",\n        \"DescriptionEnglish\": \"Dahomey\",\n        \"Description\": \"داهومي\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"892\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"بوركينافاسو\",\n        \"NationalityEnu\": \"BURKINA FASO\",\n        \"DescriptionArabic\": \"بوركينافاسو\",\n        \"DescriptionEnglish\": \"Burkina Faso\",\n        \"Description\": \"بوركينافاسو\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"822\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"نيكارغويه\",\n        \"NationalityEnu\": \"NICARAGUA\",\n        \"DescriptionArabic\": \"نيكارغوا\",\n        \"DescriptionEnglish\": \"Nicaragua\",\n        \"Description\": \"نيكارغوا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"501\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"PhoneCode\": \"234\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"نيجيرية\",\n        \"NationalityEnu\": \"NIGERIAN\",\n        \"DescriptionArabic\": \"نيجيريا\",\n        \"DescriptionEnglish\": \"Nigeria\",\n        \"Description\": \"نيجيريا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"539\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"جزر رونيو\",\n        \"NationalityEnu\": \"جزر رونيو\",\n        \"DescriptionArabic\": \"جزر رونيو\",\n        \"DescriptionEnglish\": \"جزر رونيو\",\n        \"Description\": \"جزر رونيو\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"769\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"غواميه\",\n        \"NationalityEnu\": \"GUAM\",\n        \"DescriptionArabic\": \"غوام\",\n        \"DescriptionEnglish\": \"Guam\",\n        \"Description\": \"غوام\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"690\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"بلغارية\",\n        \"NationalityEnu\": \"BULGARIAN\",\n        \"DescriptionArabic\": \"بلغاريا\",\n        \"DescriptionEnglish\": \"Bulgaria\",\n        \"Description\": \"بلغاريا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"725\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"وان كوري\",\n        \"CurrencyValue\": 2600,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:38:35.807Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"كوريا الجنوبية\",\n        \"NationalityEnu\": \"SOUTH KOREA\",\n        \"DescriptionArabic\": \"كوريا الجنوبية\",\n        \"DescriptionEnglish\": \"South Korea\",\n        \"Description\": \"كوريا الجنوبية\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:38:35.807Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"522\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"الكمرون\",\n        \"NationalityEnu\": \"CAMEROONIAN\",\n        \"DescriptionArabic\": \"الكمرون\",\n        \"DescriptionEnglish\": \"Cameroon\",\n        \"Description\": \"الكمرون\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-12-12T13:13:37.802Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"505\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"ليبيرية\",\n        \"NationalityEnu\": \"LIBERIAN\",\n        \"DescriptionArabic\": \"ليبيرية\",\n        \"DescriptionEnglish\": \"Liberia\",\n        \"Description\": \"ليبيرية\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"904\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"قرغيزيه\",\n        \"NationalityEnu\": \"QARGEEZIAN\",\n        \"DescriptionArabic\": \"قرغيزيا\",\n        \"DescriptionEnglish\": \"Qargeezia\",\n        \"Description\": \"قرغيزيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"341\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"دينار جزائري\",\n        \"CurrencyValue\": 350,\n        \"LastCurrencyUpdate\": \"2021-05-06T11:05:13.532Z\",\n        \"PhoneCode\": \"213\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"جزائرية\",\n        \"NationalityEnu\": \"ALGERIAN\",\n        \"DescriptionArabic\": \"الجزائر\",\n        \"DescriptionEnglish\": \"Algeria\",\n        \"Description\": \"الجزائر\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-05-06T11:05:13.532Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"726\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"لاوس\",\n        \"NationalityEnu\": \"LAOTIAN\",\n        \"DescriptionArabic\": \"لاوس\",\n        \"DescriptionEnglish\": \"Laos\",\n        \"Description\": \"لاوس\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"681\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"تشيكيه\",\n        \"NationalityEnu\": \"CZECH\",\n        \"DescriptionArabic\": \"التشيك\",\n        \"DescriptionEnglish\": \"Al Czech\",\n        \"Description\": \"التشيك\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"775\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"نيو\",\n        \"NationalityEnu\": \"NIUE\",\n        \"DescriptionArabic\": \"نيو\",\n        \"DescriptionEnglish\": \"Niue\",\n        \"Description\": \"نيو\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"518\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"نيجيرية\",\n        \"NationalityEnu\": \"NIGERIAN\",\n        \"DescriptionArabic\": \"النيجر\",\n        \"DescriptionEnglish\": \"Niger\",\n        \"Description\": \"النيجر\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"111\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyValue\": 150,\n        \"LastCurrencyUpdate\": \"2019-06-02T11:14:56.376Z\",\n        \"PhoneCode\": \"230\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"موريشوسيه\",\n        \"NationalityEnu\": \"MAURITIAN\",\n        \"DescriptionArabic\": \"موريشوس\",\n        \"DescriptionEnglish\": \"Mauritius\",\n        \"Description\": \"موريشوس\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-06-02T11:14:56.376Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"691\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"هنجارية\",\n        \"NationalityEnu\": \"HUNGARIAN\",\n        \"DescriptionArabic\": \"هنجاريا\",\n        \"DescriptionEnglish\": \"Hungary\",\n        \"Description\": \"هنجاريا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"735\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"سيكيم\",\n        \"NationalityEnu\": \"سيكيم\",\n        \"DescriptionArabic\": \"سيكيم\",\n        \"DescriptionEnglish\": \"سيكيم\",\n        \"Description\": \"سيكيم\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"761\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"ساموا\",\n        \"NationalityEnu\": \"SAMWA\",\n        \"DescriptionArabic\": \"ساموا\",\n        \"DescriptionEnglish\": \"Samwa\",\n        \"Description\": \"ساموا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"658\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"طاجكستانيه\",\n        \"NationalityEnu\": \"TAGIK\",\n        \"DescriptionArabic\": \"طاجكستان\",\n        \"DescriptionEnglish\": \"Tajikistan\",\n        \"Description\": \"طاجكستان\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"720\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"ليرة تركية\",\n        \"CurrencyValue\": 13,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:24:45.883Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"تركية\",\n        \"NationalityEnu\": \"TURKISH\",\n        \"DescriptionArabic\": \"تركيا\",\n        \"DescriptionEnglish\": \"Turkey\",\n        \"Description\": \"تركيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-01-06T11:29:41.381Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"654\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"ارمينيه\",\n        \"NationalityEnu\": \"ARMANIAN\",\n        \"DescriptionArabic\": \"ارمينيا\",\n        \"DescriptionEnglish\": \"Armenia\",\n        \"Description\": \"ارمينيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"764\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"جكوك\",\n        \"NationalityEnu\": \"جكوك\",\n        \"DescriptionArabic\": \"جكوك\",\n        \"DescriptionEnglish\": \"جكوك\",\n        \"Description\": \"جكوك\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"882\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"أكوادور\",\n        \"NationalityEnu\": \"ECUADORAN\",\n        \"DescriptionArabic\": \"أكوادور\",\n        \"DescriptionEnglish\": \"Ecuador\",\n        \"Description\": \"أكوادور\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-12-17T13:02:43.987Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"849\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"سانت مارتن\",\n        \"NationalityEnu\": \"SINT MAARTEN\",\n        \"DescriptionArabic\": \"سانت مارتن\",\n        \"DescriptionEnglish\": \"Sint Maarten\",\n        \"Description\": \"سانت مارتن\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"641\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"يورو\",\n        \"CurrencyValue\": 2.25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:32:06.798Z\",\n        \"PhoneCode\": \"32\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"بلجيكية\",\n        \"NationalityEnu\": \"BELGIAN\",\n        \"DescriptionArabic\": \"بلجيكا\",\n        \"DescriptionEnglish\": \"Belgium\",\n        \"Description\": \"بلجيكا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:32:06.798Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"507\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"تنزانية\",\n        \"NationalityEnu\": \"TANZANIAN\",\n        \"DescriptionArabic\": \"تنزانيا\",\n        \"DescriptionEnglish\": \"Tanzania\",\n        \"Description\": \"تنزانيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"682\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"سلوفاكيه\",\n        \"NationalityEnu\": \"SLOVAKIAN\",\n        \"DescriptionArabic\": \"سلوفاكيا\",\n        \"DescriptionEnglish\": \"Slovakia\",\n        \"Description\": \"سلوفاكيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"900\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"اسكتلنديه\",\n        \"NationalityEnu\": \"SCOTISH\",\n        \"DescriptionArabic\": \"اسكتلندا\",\n        \"DescriptionEnglish\": \"Scotland\",\n        \"Description\": \"اسكتلندا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-12-19T10:39:34.908Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"517\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"سيراليون\",\n        \"NationalityEnu\": \"SEIRRALEONE\",\n        \"DescriptionArabic\": \"سيراليون\",\n        \"DescriptionEnglish\": \"Seirraleone\",\n        \"Description\": \"سيراليون\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"870\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"دولار أمريكي\",\n        \"CurrencyValue\": 2.25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:38:21.368Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"تشيليه\",\n        \"NationalityEnu\": \"CHILEAN\",\n        \"DescriptionArabic\": \"تشيلي\",\n        \"DescriptionEnglish\": \"Chile\",\n        \"Description\": \"تشيلي\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:38:21.368Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"844\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"بورتوريكيه\",\n        \"NationalityEnu\": \"PUERTORICAN\",\n        \"DescriptionArabic\": \"بورتوريكو\",\n        \"DescriptionEnglish\": \"Puerto Rico\",\n        \"Description\": \"بورتوريكو\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"555\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"PhoneCode\": \"1-268\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"انتيغوا و باربودا\",\n        \"NationalityEnu\": \"ANTIGUAN AND BARBUDAN\",\n        \"DescriptionArabic\": \"انتيغوا و باربودا\",\n        \"DescriptionEnglish\": \"ANTIGUA AND BARBUDA\",\n        \"Description\": \"انتيغوا و باربودا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"657\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"دولار أمريكي\",\n        \"CurrencyValue\": 2.25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:24:12.899Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"كازخستانيه\",\n        \"NationalityEnu\": \"KAZAKHISTAN\",\n        \"DescriptionArabic\": \"كازخستان\",\n        \"DescriptionEnglish\": \"kazakhistan\",\n        \"Description\": \"كازخستان\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:24:12.899Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"533\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"بولندية\",\n        \"NationalityEnu\": \"POLISH\",\n        \"DescriptionArabic\": \"بولندا\",\n        \"DescriptionEnglish\": \"Poland\",\n        \"Description\": \"بولندا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"836\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"بيرميويا\",\n        \"NationalityEnu\": \"بيرميويا\",\n        \"DescriptionArabic\": \"بيرميويا\",\n        \"DescriptionEnglish\": \"بيرميويا\",\n        \"Description\": \"بيرميويا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"841\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"مارتينيد\",\n        \"NationalityEnu\": \"MARTINIQUE\",\n        \"DescriptionArabic\": \"مارتينيد\",\n        \"DescriptionEnglish\": \"Martinique\",\n        \"Description\": \"مارتينيد\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"520\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"توجو\",\n        \"NationalityEnu\": \"TOGOLESE\",\n        \"DescriptionArabic\": \"توجو\",\n        \"DescriptionEnglish\": \"Togo\",\n        \"Description\": \"توجو\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"631\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"PhoneCode\": \"379\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"الفاتيكان\",\n        \"NationalityEnu\": \"VATICAN\",\n        \"DescriptionArabic\": \"الفاتيكان\",\n        \"DescriptionEnglish\": \"Vatican City\",\n        \"Description\": \"الفاتيكان\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"649\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"لكسمبرغ\",\n        \"NationalityEnu\": \"LUXEMBURG\",\n        \"DescriptionArabic\": \"لكسمبرغ\",\n        \"DescriptionEnglish\": \"Luxemburg\",\n        \"Description\": \"لكسمبرغ\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"716\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"بنغاليه\",\n        \"NationalityEnu\": \"BANGLADESHI\",\n        \"DescriptionArabic\": \"بنغلادش\",\n        \"DescriptionEnglish\": \"Bangladesh\",\n        \"Description\": \"بنغلادش\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"536\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"موزمبيقية\",\n        \"NationalityEnu\": \"MOZAMBICAN\",\n        \"DescriptionArabic\": \"موزمبيق\",\n        \"DescriptionEnglish\": \"Mozambigue\",\n        \"Description\": \"موزمبيق\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"875\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"أرجنتينيه\",\n        \"NationalityEnu\": \"ARGENTINIAN\",\n        \"DescriptionArabic\": \"الأرجنتين\",\n        \"DescriptionEnglish\": \"Argentina\",\n        \"Description\": \"الأرجنتين\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-03-18T10:59:35.983Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"546\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"شيلينغ كيني\",\n        \"CurrencyValue\": 1.5,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"لوكسمبورغية\",\n        \"NationalityEnu\": \"LUXEMBOURG\",\n        \"DescriptionArabic\": \"لوكسمبورغ\",\n        \"DescriptionEnglish\": \"Luxembourg\",\n        \"Description\": \"لوكسمبورغ\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"504\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"شيلينغ كيني\",\n        \"CurrencyValue\": 230,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:45:48.294Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"كينية\",\n        \"NationalityEnu\": \"KENYAN\",\n        \"DescriptionArabic\": \"كينيا\",\n        \"DescriptionEnglish\": \"Kenya\",\n        \"Description\": \"كينيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:45:48.294Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"829\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"غواتيماليه\",\n        \"NationalityEnu\": \"GUATEMALAN\",\n        \"DescriptionArabic\": \"غواتيمالا\",\n        \"DescriptionEnglish\": \"Guatemala\",\n        \"Description\": \"غواتيمالا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"750\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"دولار أسترالي\",\n        \"CurrencyValue\": 3.5,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:40:34.430Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"استرالية\",\n        \"NationalityEnu\": \"AUSTRALIAN\",\n        \"DescriptionArabic\": \"استراليا\",\n        \"DescriptionEnglish\": \"Australia\",\n        \"Description\": \"استراليا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-03-14T09:08:54.187Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"530\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"كونجو\",\n        \"NationalityEnu\": \"CONGO\",\n        \"DescriptionArabic\": \"كونجو\",\n        \"DescriptionEnglish\": \"Congo\",\n        \"Description\": \"كونجو\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"534\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"افريقيا الجنوبية\",\n        \"NationalityEnu\": \"SOUTH AFRICA\",\n        \"DescriptionArabic\": \"افريقيا الجنوبية\",\n        \"DescriptionEnglish\": \"South Africa\",\n        \"Description\": \"افريقيا الجنوبية\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-12-12T09:15:44.133Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"772\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"كلدونينيه\",\n        \"NationalityEnu\": \"كلدونينيه\",\n        \"DescriptionArabic\": \"كلدونيا\",\n        \"DescriptionEnglish\": \"كلدونيا\",\n        \"Description\": \"كلدونيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"640\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"يورو\",\n        \"CurrencyValue\": 2.25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:40:10.031Z\",\n        \"PhoneCode\": \"43\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"نمساوية\",\n        \"NationalityEnu\": \"AUSTRIAN\",\n        \"DescriptionArabic\": \"النمسا\",\n        \"DescriptionEnglish\": \"Austria\",\n        \"Description\": \"النمسا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:40:10.032Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"610\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"جنيه استرليني\",\n        \"CurrencyValue\": 2,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:42:23.523Z\",\n        \"PhoneCode\": \"44\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"بريطانية\",\n        \"NationalityEnu\": \"BRITISH\",\n        \"DescriptionArabic\": \"بريطانيا\",\n        \"DescriptionEnglish\": \"UNITED KINGDOM\",\n        \"Description\": \"بريطانيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:42:23.523Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"315\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"دينار بحريني\",\n        \"CurrencyValue\": 1,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:43:58.772Z\",\n        \"PhoneCode\": \"973\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"بحرينية\",\n        \"NationalityEnu\": \"BAHRAINI\",\n        \"DescriptionArabic\": \"البحرين\",\n        \"DescriptionEnglish\": \"Bahrain\",\n        \"Description\": \"البحرين\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-09-09T10:44:38.040Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"545\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"جزر الرأس الاخضر\",\n        \"NationalityEnu\": \"LABO CAMARINES NORTE\",\n        \"DescriptionArabic\": \"جزر الرأس الاخضر\",\n        \"DescriptionEnglish\": \"Labo Camarines Norte\",\n        \"Description\": \"جزر الرأس الاخضر\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"727\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"بورما\",\n        \"NationalityEnu\": \"BURMESE\",\n        \"DescriptionArabic\": \"بورما\",\n        \"DescriptionEnglish\": \"Burma\",\n        \"Description\": \"بورما\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"541\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"جزر سيشل\",\n        \"NationalityEnu\": \"SEYCHELLES\",\n        \"DescriptionArabic\": \"جزر سيشل\",\n        \"DescriptionEnglish\": \"Seychelles\",\n        \"Description\": \"جزر سيشل\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"351\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"PhoneCode\": \"252\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"صومالية\",\n        \"NationalityEnu\": \"SOMALI\",\n        \"DescriptionArabic\": \"الصومال\",\n        \"DescriptionEnglish\": \"Somalia\",\n        \"Description\": \"الصومال\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"824\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"ترينيداد/ توباغو\",\n        \"NationalityEnu\": \"TRINIDAD TOBAGO\",\n        \"DescriptionArabic\": \"ترينيداد/ توباغو\",\n        \"DescriptionEnglish\": \"Trinidad/Tobago\",\n        \"Description\": \"ترينيداد/ توباغو\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"519\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"غينية\",\n        \"NationalityEnu\": \"GUINEAN\",\n        \"DescriptionArabic\": \"غينيا\",\n        \"DescriptionEnglish\": \"Guinea\",\n        \"Description\": \"غينيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"638\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"يورو\",\n        \"CurrencyValue\": 1.5,\n        \"PhoneCode\": \"353\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"ايرلندية\",\n        \"NationalityEnu\": \"IRISH\",\n        \"DescriptionArabic\": \"ايرلندا\",\n        \"DescriptionEnglish\": \"Ireland\",\n        \"Description\": \"ايرلندا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"620\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"يورو\",\n        \"CurrencyValue\": 2.25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:42:09.963Z\",\n        \"PhoneCode\": \"31\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"هولاندية\",\n        \"NationalityEnu\": \"DUTCH\",\n        \"DescriptionArabic\": \"هولندا\",\n        \"DescriptionEnglish\": \"NETHERLANDS\",\n        \"Description\": \"هولندا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:42:09.963Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"693\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"مجري\",\n        \"NationalityEnu\": \"ALMAJAR\",\n        \"DescriptionArabic\": \"المجر\",\n        \"DescriptionEnglish\": \"ALMAJAR\",\n        \"Description\": \"المجر\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"838\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"كابمان\",\n        \"NationalityEnu\": \"كابمان\",\n        \"DescriptionArabic\": \"كابمان\",\n        \"DescriptionEnglish\": \"كابمان\",\n        \"Description\": \"كابمان\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"840\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"غواديلون\",\n        \"NationalityEnu\": \"GUADELOUPE\",\n        \"DescriptionArabic\": \"غواديلون\",\n        \"DescriptionEnglish\": \"Guadeloupe\",\n        \"Description\": \"غواديلون\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"847\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"سانت بيير\",\n        \"NationalityEnu\": \"SAINT PRERRE\",\n        \"DescriptionArabic\": \"سانت بيير\",\n        \"DescriptionEnglish\": \"Saint Prerre\",\n        \"Description\": \"سانت بيير\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"639\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"ايسلندية\",\n        \"NationalityEnu\": \"ICELANDER\",\n        \"DescriptionArabic\": \"ايسلند\",\n        \"DescriptionEnglish\": \"Iceland\",\n        \"Description\": \"ايسلند\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"742\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"ريوكو\",\n        \"NationalityEnu\": \"ريوكو\",\n        \"DescriptionArabic\": \"ريوكو\",\n        \"DescriptionEnglish\": \"ريوكو\",\n        \"Description\": \"ريوكو\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"901\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"يورو\",\n        \"CurrencyValue\": 1.5,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"مولدوفيه\",\n        \"NationalityEnu\": \"MOLDOVIAN\",\n        \"DescriptionArabic\": \"مولدوفا\",\n        \"DescriptionEnglish\": \"Moldova\",\n        \"Description\": \"مولدوفا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"660\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"يورو\",\n        \"CurrencyValue\": 2.25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:29:43.376Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"رومانية\",\n        \"NationalityEnu\": \"ROMANIAN\",\n        \"DescriptionArabic\": \"رومانيا\",\n        \"DescriptionEnglish\": \"Romania\",\n        \"Description\": \"رومانيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:29:43.376Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"823\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"بنميه\",\n        \"NationalityEnu\": \"PANAMANIAN\",\n        \"DescriptionArabic\": \"بنما\",\n        \"DescriptionEnglish\": \"Panama\",\n        \"Description\": \"بنما\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"895\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"ليتوانيه\",\n        \"NationalityEnu\": \"LITHUANIAN\",\n        \"DescriptionArabic\": \"ليتوانيا\",\n        \"DescriptionEnglish\": \"Lithuania\",\n        \"Description\": \"ليتوانيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"659\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"جورجيه\",\n        \"NationalityEnu\": \"GEORGIAN\",\n        \"DescriptionArabic\": \"جورجيا\",\n        \"DescriptionEnglish\": \"Georgia\",\n        \"Description\": \"جورجيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"770\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"ج ميرواي\",\n        \"NationalityEnu\": \"ج ميرواي\",\n        \"DescriptionArabic\": \"ج ميرواي\",\n        \"DescriptionEnglish\": \"ج ميرواي\",\n        \"Description\": \"ج ميرواي\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"821\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"كوبيه\",\n        \"NationalityEnu\": \"CUBAN\",\n        \"DescriptionArabic\": \"كوبا\",\n        \"DescriptionEnglish\": \"Cuba\",\n        \"Description\": \"كوبا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"781\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"واليسوفروتانا\",\n        \"NationalityEnu\": \"WALLIS AND FUTUNA\",\n        \"DescriptionArabic\": \"واليسوفروتانا\",\n        \"DescriptionEnglish\": \"Wallis and Futuna\",\n        \"Description\": \"واليسوفروتانا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"646\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"فنلندية\",\n        \"NationalityEnu\": \"FINN\",\n        \"DescriptionArabic\": \"فنلندا\",\n        \"DescriptionEnglish\": \"Finland\",\n        \"Description\": \"فنلندا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"779\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"تونغا\",\n        \"NationalityEnu\": \"TONGA\",\n        \"DescriptionArabic\": \"تونغا\",\n        \"DescriptionEnglish\": \"Tonga\",\n        \"Description\": \"تونغا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"714\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"افغانستانية\",\n        \"NationalityEnu\": \"AFGHAN\",\n        \"DescriptionArabic\": \"افغانستان\",\n        \"DescriptionEnglish\": \"Afghanistan\",\n        \"Description\": \"افغانستان\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-03-15T09:14:38.784Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"002\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"شيكل إسرائيلي\",\n        \"CurrencyValue\": 9,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:37:09.040Z\",\n        \"PhoneCode\": \"970\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"فلسطيني\",\n        \"NationalityEnu\": \"PALESTINIAN\",\n        \"DescriptionArabic\": \"فلسطين\",\n        \"DescriptionEnglish\": \"Palestine\",\n        \"Description\": \"فلسطين\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-02-28T07:40:09.147Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"353\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"PhoneCode\": \"253\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"جيبوتية\",\n        \"NationalityEnu\": \"DGIBOUTIAN\",\n        \"DescriptionArabic\": \"جيبوتي\",\n        \"DescriptionEnglish\": \"Djibouti\",\n        \"Description\": \"جيبوتي\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"554\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"PhoneCode\": \"64\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"نيوزلندية\",\n        \"NationalityEnu\": \"NEW ZEALAND\",\n        \"DescriptionArabic\": \"نيوزيلندا\",\n        \"DescriptionEnglish\": \"New Zealand\",\n        \"Description\": \"نيوزيلندا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"834\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"انتينيه\",\n        \"NationalityEnu\": \"انتينيه\",\n        \"DescriptionArabic\": \"انتينا\",\n        \"DescriptionEnglish\": \"انتينا\",\n        \"Description\": \"انتينا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"661\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"تركمانستانيه\",\n        \"NationalityEnu\": \"TURKMENISTANI\",\n        \"DescriptionArabic\": \"تركمانستان\",\n        \"DescriptionEnglish\": \"Turkmenistan\",\n        \"Description\": \"تركمانستان\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"521\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"زمبيق\",\n        \"NationalityEnu\": \"ZAMBIGUE\",\n        \"DescriptionArabic\": \"زمبيق\",\n        \"DescriptionEnglish\": \"zambigue\",\n        \"Description\": \"زمبيق\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"515\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"ناميبيا\",\n        \"NationalityEnu\": \"NAMIBIAN\",\n        \"DescriptionArabic\": \"ناميبيا\",\n        \"DescriptionEnglish\": \"Namibia\",\n        \"Description\": \"ناميبيا\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"Qui\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"Et aut deserunt nisi commodo libero\",\n        \"PhoneCode\": \"In volu\",\n        \"RestrictedExport\": \"1\",\n        \"CurrencyNameEnu\": \"Debitis non culpa temporibus cupiditate perspiciatis dolores\",\n        \"NationalityAra\": \"Minima ex ullamco commodi in id fugiat deserunt rerum sit saepe nesciunt vel dolores\",\n        \"NationalityEnu\": \"Laborum Quis aute aut tenetur quis quod corrupti cupiditate repudiandae ut qui quis voluptas eiusmod pariatur Fugit\",\n        \"DescriptionArabic\": \"الوصف بالعربي\",\n        \"DescriptionEnglish\": \"Ex aut adipisicing sit suscipit consectetur neque reprehenderit enim est eos et\",\n        \"Description\": \"الوصف بالعربي\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-09-14T11:06:59.128Z\",\n        \"createdDate\": \"2021-09-14T11:06:48.339Z\"\n    },\n    {\n        \"ISO_Code\": \"999\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"دينار\",\n        \"PhoneCode\": \"962\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"اردنية\",\n        \"DescriptionArabic\": \"الاردن سفارة\",\n        \"DescriptionEnglish\": \"jordan s\",\n        \"Description\": \"الاردن سفارة\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-10-21T06:44:10.282Z\",\n        \"createdDate\": \"2021-10-21T06:43:10.491Z\"\n    }\n]"
				}
			]
		},
		{
			"name": "Get Applicant Data",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\r\n    \"NAT_NO\": \"1234560\"\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://10.0.52.241/birthcertificate/applicantes",
					"protocol": "https",
					"host": [
						"10",
						"0",
						"52",
						"241"
					],
					"path": [
						"birthcertificate",
						"applicantes"
					]
				},
				"description": "API endpoint to **Fetch Data foer an applicant** in the system .\n\n> A Successful API Request Will result in a **HTTP 200** status code .\n> \n> Request for non existing Applicant will return **HTTP 400** status code"
			},
			"response": [
				{
					"name": "Get Applicant Data",
					"originalRequest": {
						"method": "POST",
						"header": [],
						"body": {
							"mode": "raw",
							"raw": "{\r\n    \"NAT_NO\": \"9932028787\"\r\n}",
							"options": {
								"raw": {
									"language": "json"
								}
							}
						},
						"url": {
							"raw": "http://10.0.52.243:8080/birthcertificate/applicantes",
							"protocol": "http",
							"host": [
								"10",
								"0",
								"52",
								"243"
							],
							"port": "8080",
							"path": [
								"birthcertificate",
								"applicantes"
							]
						}
					},
					"status": "OK",
					"code": 200,
					"_postman_previewlanguage": "json",
					"header": [
						{
							"key": "Date",
							"value": "Sun, 27 Mar 2022 07:42:06 GMT"
						},
						{
							"key": "Cache-Control",
							"value": "no-store"
						},
						{
							"key": "Content-Type",
							"value": "application/json;charset=utf-8"
						},
						{
							"key": "Content-Length",
							"value": "616"
						}
					],
					"cookie": [],
					"body": "{\n    \"FirstName\": \"هديل\",\n    \"SecondName\": \"فؤاد\",\n    \"ThirdName\": \"سالم\",\n    \"FamilyName\": \"عيسوه\",\n    \"Beneficiariess\": [\n        {\n            \"Name_Relation\": \"جبران فؤاد - إبن            \",\n            \"Nat_no\": \"9881005839\"\n        },\n        {\n            \"Name_Relation\": \"بشاره فؤاد - إبن            \",\n            \"Nat_no\": \"9981054636\"\n        },\n        {\n            \"Name_Relation\": \"فؤاد سالم - رب الاسرة      \",\n            \"Nat_no\": \"9551004578\"\n        },\n        {\n            \"Name_Relation\": \"وفاء يعقوب - زوجة           \",\n            \"Nat_no\": \"9642014055\"\n        },\n        {\n            \"Name_Relation\": \"هديل فؤاد - إبنة           \",\n            \"Nat_no\": \"9932028787\"\n        },\n        {\n            \"Name_Relation\": \"دانا فؤاد - إبنة           \",\n            \"Nat_no\": \"9902026301\"\n        }\n    ]\n}"
				},
				{
					"name": "Get Applicant Data_ErrorResponse",
					"originalRequest": {
						"method": "POST",
						"header": [],
						"body": {
							"mode": "raw",
							"raw": "{\r\n    \"NAT_NO\": \"12\"\r\n}",
							"options": {
								"raw": {
									"language": "json"
								}
							}
						},
						"url": {
							"raw": "http://10.0.52.243:8080/birthcertificate/applicantes",
							"protocol": "http",
							"host": [
								"10",
								"0",
								"52",
								"243"
							],
							"port": "8080",
							"path": [
								"birthcertificate",
								"applicantes"
							]
						}
					},
					"status": "No Data Found , Make sure that the entered National Number is correct",
					"code": 404,
					"_postman_previewlanguage": "json",
					"header": [
						{
							"key": "Date",
							"value": "Sun, 27 Mar 2022 07:45:06 GMT"
						},
						{
							"key": "Cache-Control",
							"value": "no-store"
						},
						{
							"key": "Content-Type",
							"value": "application/json;charset=utf-8"
						},
						{
							"key": "Content-Length",
							"value": "82"
						}
					],
					"cookie": [],
					"body": "{\n    \"Error\": \"No Data Found , Make sure that the entered National Number is correct\"\n}"
				}
			]
		},
		{
			"name": "Get Beneficiary Birth Data",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\r\n    \"NAT_NO\": \"1234560\"\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://10.0.52.241/birthcertificate/beneficiaries",
					"protocol": "https",
					"host": [
						"10",
						"0",
						"52",
						"241"
					],
					"path": [
						"birthcertificate",
						"beneficiaries"
					]
				},
				"description": "API endpoint to **Fetch The Birth Data for the applicant's beneficiery** in the system .\n\n> A Successful API Request Will result in a **HTTP 200** status code .\n> \n> Request for non existing Applicant will return **HTTP 400** status code"
			},
			"response": [
				{
					"name": "Get Beneficiary Birth Data",
					"originalRequest": {
						"method": "POST",
						"header": [],
						"body": {
							"mode": "raw",
							"raw": "{\r\n    \"NAT_NO\": \"9881005839\"\r\n}",
							"options": {
								"raw": {
									"language": "json"
								}
							}
						},
						"url": {
							"raw": "http://10.0.52.243:8080/birthcertificate/beneficiaries",
							"protocol": "http",
							"host": [
								"10",
								"0",
								"52",
								"243"
							],
							"port": "8080",
							"path": [
								"birthcertificate",
								"beneficiaries"
							]
						}
					},
					"status": "OK",
					"code": 200,
					"_postman_previewlanguage": "json",
					"header": [
						{
							"key": "Date",
							"value": "Sun, 27 Mar 2022 07:50:28 GMT"
						},
						{
							"key": "Cache-Control",
							"value": "no-store"
						},
						{
							"key": "Content-Type",
							"value": "application/json;charset=utf-8"
						},
						{
							"key": "Content-Length",
							"value": "1423"
						}
					],
					"cookie": [],
					"body": "{\n    \"FirstNameARA\": \"جبران\",\n    \"SecondNameARA\": \"فؤاد\",\n    \"ThirdNameARA\": \"سالم\",\n    \"FamilyNameARA\": \"عيسوه\",\n    \"FirstNameENU\": \"Jubran\",\n    \"SecondNameENU\": \"Fuad\",\n    \"ThirdNameENU\": \"Salem\",\n    \"FamilyNameENU\": \"Eisouh\",\n    \"Gender\": \"Male\",\n    \"NationalId\": \"9881005839\",\n    \"BirthDate\": \"1988-06-28T00:00:00.000Z\",\n    \"FFirstNameARA\": \"فؤاد\",\n    \"FSecondNameARA\": \"سالم\",\n    \"FFamilyNameARA\": \"عيسوه\",\n    \"MFirstNameARA\": \"وفاء\",\n    \"MSecondNameARA\": \"يعقوب\",\n    \"MFamilyNameARA\": \"مراد\",\n    \"MFirstNameENU\": \"Wafa\",\n    \"FSecondNameENU\": \"Salem\",\n    \"FFamilyNameENU\": \"Eisouh\",\n    \"EnglishNameInd\": false,\n    \"CivilOffice\": \"عجلون\",\n    \"CivilRegistrationNumber\": \"024/073\",\n    \"ReligionARA\": \"Christian\",\n    \"SerialNumber\": \"9881005839\",\n    \"FullName\": \"جبران فؤاد سالم عيسوه\",\n    \"PlaceOfBirthARA\": \"عجلون\",\n    \"PlaceOfBirthENU\": \"AJLOUN\",\n    \"FatherReligionARA\": \"Christian\",\n    \"MotherReligionARA\": \"Christian\",\n    \"FatherReligionENU\": \"Christian\",\n    \"MotherReligionENU\": \"Christian\",\n    \"ReligionENU\": \"Christian\",\n    \"FFirstNameENU\": \"Fuad\",\n    \"WrittenDateARA\": \"الثامن والعشرون من حزيــــــران لعام الف وتسعمائه و ثمانية وثمانين ميلادي\",\n    \"WrittenDateENU\": \" Twenty Eighth OF June Nineteen Eighty Eight\",\n    \"CivilStatus\": \"Live\",\n    \"MSecondNameENU\": \"Yacoub\",\n    \"MFamilyNameENU\": \"Murad\",\n    \"ArNationality\": \"اردني\",\n    \"EnNationality\": \"JORDANIAN\",\n    \"EventNumber\": \"00040/000837\",\n    \"BirthRegisterType\": \"3\",\n    \"CheckDigit\": \"ع\",\n    \"CivilOfficeENU\": \"AJLOUN\",\n    \"WantedInd\": false\n}"
				},
				{
					"name": "Get Beneficiary Birth Data_ErrorResponse",
					"originalRequest": {
						"method": "POST",
						"header": [],
						"body": {
							"mode": "raw",
							"raw": "{\r\n    \"NAT_NO\": \"12\"\r\n}",
							"options": {
								"raw": {
									"language": "json"
								}
							}
						},
						"url": {
							"raw": "http://10.0.52.243:8080/birthcertificate/beneficiaries",
							"protocol": "http",
							"host": [
								"10",
								"0",
								"52",
								"243"
							],
							"port": "8080",
							"path": [
								"birthcertificate",
								"beneficiaries"
							]
						}
					},
					"status": "No Data Found , Make sure that the entered National Number is correct",
					"code": 404,
					"_postman_previewlanguage": "json",
					"header": [
						{
							"key": "Date",
							"value": "Sun, 27 Mar 2022 07:52:56 GMT"
						},
						{
							"key": "Cache-Control",
							"value": "no-store"
						},
						{
							"key": "Content-Type",
							"value": "application/json;charset=utf-8"
						},
						{
							"key": "Content-Length",
							"value": "82"
						}
					],
					"cookie": [],
					"body": "{\n    \"Error\": \"No Data Found , Make sure that the entered National Number is correct\"\n}"
				}
			]
		},
		{
			"name": "Fees Calculation",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\r\n \"DeliveryCountryCode\":\"001\",\r\n \"ServiceType\":\"Birth_Certificate\",\r\n \"DeliveryType\":\"Aramex\",\r\n \"arabicCopies\":2,\r\n \"EnglishCopies\":1\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://10.0.52.241/birthcertificate/fees",
					"protocol": "https",
					"host": [
						"10",
						"0",
						"52",
						"241"
					],
					"path": [
						"birthcertificate",
						"fees"
					]
				},
				"description": "#### API endpoint to calculate the fees for the requested service .\n\n> A Successful API Request Will result in a **HTTP 200** status code .\n> \n> Request for non existing Applicant will return **HTTP 400** status code"
			},
			"response": [
				{
					"name": "Fees Calculation",
					"originalRequest": {
						"method": "POST",
						"header": [],
						"body": {
							"mode": "raw",
							"raw": "{\r\n \"DeliveryCountryCode\":\"001\",\r\n \"ServiceType\":\"Birth_Certificate\",\r\n \"DeliveryType\":\"Aramex\",\r\n \"arabicCopies\":2,\r\n \"EnglishCopies\":1\r\n}",
							"options": {
								"raw": {
									"language": "json"
								}
							}
						},
						"url": {
							"raw": "https://10.0.52.241/birthcertificate/fees",
							"protocol": "https",
							"host": [
								"10",
								"0",
								"52",
								"241"
							],
							"path": [
								"birthcertificate",
								"fees"
							]
						}
					},
					"status": "Success",
					"code": 200,
					"_postman_previewlanguage": "json",
					"header": [
						{
							"key": "Date",
							"value": "Sun, 27 Mar 2022 08:05:44 GMT"
						},
						{
							"key": "Server",
							"value": "Apache/2.4.28 (Win64) OpenSSL/1.1.0f"
						},
						{
							"key": "X-Frame-Options",
							"value": "SAMEORIGIN"
						},
						{
							"key": "Cache-Control",
							"value": "no-store"
						},
						{
							"key": "Content-Type",
							"value": "application-Json;charset=utf-8"
						},
						{
							"key": "Content-Length",
							"value": "210"
						},
						{
							"key": "Keep-Alive",
							"value": "timeout=5, max=100"
						},
						{
							"key": "Connection",
							"value": "Keep-Alive"
						},
						{
							"key": "Set-Cookie",
							"value": "COOKI3=ffffffff09082ae145525d5f4f58455e445a4a42378b;expires=Sun, 27-Mar-2022 08:07:44 GMT;path=/;secure;httponly"
						}
					],
					"cookie": [],
					"body": "[\n    {\n        \"FeeType\": \"Certificate_Issuance_Arabic\",\n        \"FeeAmount\": 2,\n        \"CopiesNumber\": 2\n    },\n    {\n        \"FeeType\": \"Certificate_Issuance_English\",\n        \"FeeAmount\": 1,\n        \"CopiesNumber\": 1\n    },\n    {\n        \"FeeType\": \"Delivery_Fees\",\n        \"FeeAmount\": 3.48,\n        \"CopiesNumber\": 0\n    }\n]"
				},
				{
					"name": "Fees Calculation_ErrorResponse",
					"originalRequest": {
						"method": "POST",
						"header": [],
						"body": {
							"mode": "raw",
							"raw": "{\r\n \"DeliveryCountryCode\":\"001\",\r\n \"ServiceType\":\"Birth_Certificate\",\r\n \"DeliveryType\":\"\",\r\n \"arabicCopies\":0,\r\n \"EnglishCopies\":1\r\n}",
							"options": {
								"raw": {
									"language": "json"
								}
							}
						},
						"url": {
							"raw": "https://10.0.52.241/birthcertificate/fees",
							"protocol": "https",
							"host": [
								"10",
								"0",
								"52",
								"241"
							],
							"path": [
								"birthcertificate",
								"fees"
							]
						}
					},
					"status": "Failed",
					"code": 400,
					"_postman_previewlanguage": "json",
					"header": [
						{
							"key": "Date",
							"value": "Sun, 27 Mar 2022 08:08:36 GMT"
						},
						{
							"key": "Server",
							"value": "Apache/2.4.28 (Win64) OpenSSL/1.1.0f"
						},
						{
							"key": "X-Frame-Options",
							"value": "SAMEORIGIN"
						},
						{
							"key": "Cache-Control",
							"value": "no-store"
						},
						{
							"key": "Content-Type",
							"value": "application-Json;charset=utf-8"
						},
						{
							"key": "Content-Length",
							"value": "46"
						},
						{
							"key": "Connection",
							"value": "close"
						},
						{
							"key": "Set-Cookie",
							"value": "COOKI3=ffffffff09082ae145525d5f4f58455e445a4a42378b;expires=Sun, 27-Mar-2022 08:10:36 GMT;path=/;secure;httponly"
						}
					],
					"cookie": [],
					"body": "{\n   Error : The Type of Delivery is not set\n}"
				}
			]
		},
		{
			"name": "Get Prerequisit",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\r\n \"ServiceType\": \"Birth_Certificate\",\r\n \"UserLanguage\": \"ar_JO\"\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://10.0.52.241/birthcertificate/prerequisit",
					"protocol": "https",
					"host": [
						"10",
						"0",
						"52",
						"241"
					],
					"path": [
						"birthcertificate",
						"prerequisit"
					]
				},
				"description": "#### API endpoint to get the prerequisite for the requested service .\n\n> A Successful API Request Will result in a **HTTP 200** status code .\n> \n> Request for non existing Applicant will return **HTTP 400** status code"
			},
			"response": [
				{
					"name": "Get Prerequisit",
					"originalRequest": {
						"method": "POST",
						"header": [],
						"body": {
							"mode": "raw",
							"raw": "{\r\n \"ServiceType\": \"Birth_Certificate\",\r\n \"UserLanguage\": \"ar_JO\"\r\n}",
							"options": {
								"raw": {
									"language": "json"
								}
							}
						},
						"url": {
							"raw": "https://10.0.52.241/birthcertificate/prerequisit",
							"protocol": "https",
							"host": [
								"10",
								"0",
								"52",
								"241"
							],
							"path": [
								"birthcertificate",
								"prerequisit"
							]
						}
					},
					"status": "OK",
					"code": 200,
					"_postman_previewlanguage": "json",
					"header": [
						{
							"key": "Date",
							"value": "Sun, 27 Mar 2022 08:32:13 GMT"
						},
						{
							"key": "Server",
							"value": "Apache/2.4.28 (Win64) OpenSSL/1.1.0f"
						},
						{
							"key": "X-Frame-Options",
							"value": "SAMEORIGIN"
						},
						{
							"key": "Cache-Control",
							"value": "no-store"
						},
						{
							"key": "Content-Type",
							"value": "application-Json;charset=utf-8"
						},
						{
							"key": "Content-Length",
							"value": "127"
						},
						{
							"key": "Keep-Alive",
							"value": "timeout=5, max=100"
						},
						{
							"key": "Connection",
							"value": "Keep-Alive"
						},
						{
							"key": "Set-Cookie",
							"value": "COOKI3=ffffffff09082ae145525d5f4f58455e445a4a42378b;expires=Sun, 27-Mar-2022 08:34:13 GMT;path=/;secure;httponly"
						}
					],
					"cookie": [],
					"body": "{\n    \"Prerequisit\": \"<strong>إصدار شهادة ولادة لواقعة أو قيد ولادة مسجلة سابقًا</strong>\"\n}"
				},
				{
					"name": "Get Prerequisit_ErrorResponse",
					"originalRequest": {
						"method": "POST",
						"header": [],
						"body": {
							"mode": "raw",
							"raw": "{\r\n \"ServiceType\": \"\",\r\n \"UserLanguage\": \"ar_JO\"\r\n}",
							"options": {
								"raw": {
									"language": "json"
								}
							}
						},
						"url": {
							"raw": "https://10.0.52.241/birthcertificate/prerequisit",
							"protocol": "https",
							"host": [
								"10",
								"0",
								"52",
								"241"
							],
							"path": [
								"birthcertificate",
								"prerequisit"
							]
						}
					},
					"status": "The Service Is Not Found",
					"code": 404,
					"_postman_previewlanguage": "json",
					"header": [
						{
							"key": "Date",
							"value": "Sun, 27 Mar 2022 08:46:22 GMT"
						},
						{
							"key": "Server",
							"value": "Apache/2.4.28 (Win64) OpenSSL/1.1.0f"
						},
						{
							"key": "X-Frame-Options",
							"value": "SAMEORIGIN"
						},
						{
							"key": "Cache-Control",
							"value": "no-store"
						},
						{
							"key": "Content-Type",
							"value": "application-Json;charset=utf-8"
						},
						{
							"key": "Content-Length",
							"value": "42"
						},
						{
							"key": "Keep-Alive",
							"value": "timeout=5, max=100"
						},
						{
							"key": "Connection",
							"value": "Keep-Alive"
						},
						{
							"key": "Set-Cookie",
							"value": "COOKI3=ffffffff09082ae145525d5f4f58455e445a4a42378b;expires=Sun, 27-Mar-2022 08:48:22 GMT;path=/;secure;httponly"
						}
					],
					"cookie": [],
					"body": "{\n   Error : \"The Service Is Not Found\"\n }"
				}
			]
		},
		{
			"name": "Check English Name",
			"request": {
				"method": "POST",
				"header": [],
				"url": {
					"raw": "https://10.0.52.241/birthcertificate/englishname",
					"protocol": "https",
					"host": [
						"10",
						"0",
						"52",
						"241"
					],
					"path": [
						"birthcertificate",
						"englishname"
					]
				},
				"description": "#### API endpoint to check the editability for an English name for the input national number .\n\n> A Successful API Request Will result in a **HTTP 200** status code .\n> \n> Request for non existing Applicant will return **HTTP 400** status code"
			},
			"response": [
				{
					"name": "Check English Name_2",
					"originalRequest": {
						"method": "POST",
						"header": [
							{
								"key": "Content-Type",
								"name": "Content-Type",
								"value": "application/json",
								"type": "text"
							}
						],
						"body": {
							"mode": "raw",
							"raw": "{\r\n\"ServiceType\": \"Birth_Certificate\",\r\n\"NAT_NO\": \"9932020000\"\r\n}",
							"options": {
								"raw": {
									"language": "json"
								}
							}
						},
						"url": {
							"raw": "http://localhost:8083/rest/api/v1/CheckEnglishName",
							"protocol": "http",
							"host": [
								"localhost"
							],
							"port": "8083",
							"path": [
								"rest",
								"api",
								"v1",
								"CheckEnglishName"
							]
						}
					},
					"status": "OK",
					"code": 200,
					"_postman_previewlanguage": "json",
					"header": [
						{
							"key": "Date",
							"value": "Wed, 23 Mar 2022 13:54:21 GMT"
						},
						{
							"key": "Content-Type",
							"value": "application/json;charset=utf-8"
						},
						{
							"key": "Content-Length",
							"value": "119"
						}
					],
					"cookie": [],
					"body": "{\n    \"EFirstName\": \"Ayah\",\n    \"ESecondName\": \"Mohammad\",\n    \"EThirdName\": \"Ayed\",\n    \"EFamilyName\": \"Alqurashi\",\n    \"EditableEngNameInd\": false\n}"
				},
				{
					"name": "Check English Name_1",
					"originalRequest": {
						"method": "POST",
						"header": [],
						"body": {
							"mode": "raw",
							"raw": "{\r\n\"ServiceType\": \"Birth_Certificate\",\r\n\"NAT_NO\": \"9932028723\"\r\n}",
							"options": {
								"raw": {
									"language": "json"
								}
							}
						},
						"url": {
							"raw": "https://10.0.52.241/birthcertificate/englishname",
							"protocol": "https",
							"host": [
								"10",
								"0",
								"52",
								"241"
							],
							"path": [
								"birthcertificate",
								"englishname"
							]
						}
					},
					"status": "OK",
					"code": 200,
					"_postman_previewlanguage": "json",
					"header": [
						{
							"key": "Date",
							"value": "Sun, 27 Mar 2022 08:48:33 GMT"
						},
						{
							"key": "Server",
							"value": "Apache/2.4.28 (Win64) OpenSSL/1.1.0f"
						},
						{
							"key": "X-Frame-Options",
							"value": "SAMEORIGIN"
						},
						{
							"key": "Cache-Control",
							"value": "no-store"
						},
						{
							"key": "Content-Type",
							"value": "application/json;charset=utf-8"
						},
						{
							"key": "Content-Length",
							"value": "27"
						},
						{
							"key": "Keep-Alive",
							"value": "timeout=5, max=100"
						},
						{
							"key": "Connection",
							"value": "Keep-Alive"
						},
						{
							"key": "Set-Cookie",
							"value": "COOKI3=ffffffff09082ae145525d5f4f58455e445a4a42378b;expires=Sun, 27-Mar-2022 08:50:34 GMT;path=/;secure;httponly"
						}
					],
					"cookie": [],
					"body": "{\n    \"EditableEngNameInd\": true\n}"
				},
				{
					"name": "Check English Name_ErrorResponse",
					"originalRequest": {
						"method": "POST",
						"header": [],
						"body": {
							"mode": "raw",
							"raw": "{\r\n\"ServiceType\": \"Birth_Certificate\",\r\n\"NAT_NO\": \"\"\r\n}",
							"options": {
								"raw": {
									"language": "json"
								}
							}
						},
						"url": {
							"raw": "https://10.0.52.241/birthcertificate/englishname",
							"protocol": "https",
							"host": [
								"10",
								"0",
								"52",
								"241"
							],
							"path": [
								"birthcertificate",
								"englishname"
							]
						}
					},
					"status": "No Data Found for this NationalId",
					"code": 400,
					"_postman_previewlanguage": "json",
					"header": [
						{
							"key": "Date",
							"value": "Sun, 27 Mar 2022 08:49:09 GMT"
						},
						{
							"key": "Server",
							"value": "Apache/2.4.28 (Win64) OpenSSL/1.1.0f"
						},
						{
							"key": "X-Frame-Options",
							"value": "SAMEORIGIN"
						},
						{
							"key": "Cache-Control",
							"value": "no-store"
						},
						{
							"key": "Content-Type",
							"value": "application/json;charset=utf-8"
						},
						{
							"key": "Content-Length",
							"value": "46"
						},
						{
							"key": "Connection",
							"value": "close"
						},
						{
							"key": "Set-Cookie",
							"value": "COOKI3=ffffffff09082ae145525d5f4f58455e445a4a42378b;expires=Sun, 27-Mar-2022 08:51:09 GMT;path=/;secure;httponly"
						}
					],
					"cookie": [],
					"body": "{\n    \"Error\": \"No Data Found for this NationalId\"\n}"
				}
			]
		}
	]
}
