
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
					"body": "[\n    {\n        \"Code\": \"02\",\n        \"DescriptionArabic\": \"??????????/ ????????????\",\n        \"DescriptionEnglish\": \"Married\",\n        \"Description\": \"??????????/ ????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-03-20T13:28:13.441Z\",\n        \"createdDate\": \"2018-09-03T13:04:56.283Z\"\n    },\n    {\n        \"Code\": \"03\",\n        \"DescriptionArabic\": \"???????? / ??????????\",\n        \"DescriptionEnglish\": \"DIVORCE\",\n        \"Description\": \"???????? / ??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-03-08T11:01:00.017Z\",\n        \"createdDate\": \"2018-09-03T13:05:12.600Z\"\n    },\n    {\n        \"Code\": \"04\",\n        \"DescriptionArabic\": \"???????? / ??????????\",\n        \"DescriptionEnglish\": \"WIDOWED\",\n        \"Description\": \"???????? / ??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-03-16T11:29:36.394Z\",\n        \"createdDate\": \"2018-09-03T13:05:22.088Z\"\n    },\n    {\n        \"Code\": \"05\",\n        \"DescriptionArabic\": \"???????????? ???? ??????????\",\n        \"DescriptionEnglish\": \"MARRIAGE FROM FOREIGN\",\n        \"Description\": \"???????????? ???? ??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-12-24T08:36:35.994Z\",\n        \"createdDate\": \"2018-09-03T13:05:31.816Z\"\n    },\n    {\n        \"Code\": \"06\",\n        \"DescriptionArabic\": \"?????????? ??????????????\",\n        \"DescriptionEnglish\": \"WIDOWED FOREIGN\",\n        \"Description\": \"?????????? ??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-12-17T09:32:39.880Z\",\n        \"createdDate\": \"2018-09-03T13:05:44.967Z\"\n    },\n    {\n        \"Code\": \"07\",\n        \"DescriptionArabic\": \"???????? ??????????????\",\n        \"DescriptionEnglish\": \"MISS WIFE\",\n        \"Description\": \"???????? ??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-02-28T07:40:09.100Z\",\n        \"createdDate\": \"2018-09-03T13:05:58.616Z\"\n    },\n    {\n        \"Code\": \"10\",\n        \"DescriptionArabic\": \"???????? ????????????\",\n        \"DescriptionEnglish\": \"The Absent Wife\",\n        \"Description\": \"???????? ????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T13:06:48.009Z\",\n        \"createdDate\": \"2018-09-03T13:06:33.270Z\"\n    },\n    {\n        \"Code\": \"11\",\n        \"DescriptionArabic\": \"???????? ?????????? ?????????? ??????????\",\n        \"DescriptionEnglish\": \"FOREIGN WIFE JOR SON\",\n        \"Description\": \"???????? ?????????? ?????????? ??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-04-14T09:41:43.519Z\",\n        \"createdDate\": \"2018-09-03T13:07:00.270Z\"\n    },\n    {\n        \"Code\": \"01\",\n        \"DescriptionArabic\": \"????????/ ??????????\",\n        \"DescriptionEnglish\": \"Single\",\n        \"Description\": \"????????/ ??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-03-21T09:23:20.714Z\",\n        \"createdDate\": \"2020-07-29T08:02:56.202Z\"\n    },\n    {\n        \"Code\": \"Saepe repudiandae necessitatibus accusantium molestiae aspernatur a quidem aspernatur aperiam\",\n        \"DescriptionArabic\": \"?????????? ??????????????\",\n        \"DescriptionEnglish\": \"Et corporis magna nemo eos asperiores voluptate ipsam magnam eum veniam sequi\",\n        \"Description\": \"?????????? ??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-09-14T11:05:33.078Z\",\n        \"createdDate\": \"2021-09-14T11:05:22.516Z\"\n    }\n]"
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
					"body": "[\n    {\n        \"Code\": \"13\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Zarqa\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-02-17T13:14:34.485Z\",\n        \"createdDate\": \"2018-09-03T12:54:58.303Z\"\n    },\n    {\n        \"Code\": \"21\",\n        \"DescriptionArabic\": \"????????\",\n        \"DescriptionEnglish\": \"Irbid\",\n        \"Description\": \"????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-03-23T09:14:38.770Z\",\n        \"createdDate\": \"2018-09-03T12:54:58.303Z\"\n    },\n    {\n        \"Code\": \"11\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Amman\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-02-17T13:14:36.329Z\",\n        \"createdDate\": \"2018-09-03T12:54:58.303Z\"\n    },\n    {\n        \"Code\": \"22\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"Mafraq\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-03-16T11:54:15.594Z\",\n        \"createdDate\": \"2018-09-03T12:54:58.303Z\"\n    },\n    {\n        \"Code\": \"23\",\n        \"DescriptionArabic\": \"??????\",\n        \"DescriptionEnglish\": \"Jerash\",\n        \"Description\": \"??????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-11-18T13:49:35.840Z\",\n        \"createdDate\": \"2018-09-03T12:54:58.303Z\"\n    },\n    {\n        \"Code\": \"14\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"Madaba\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-11-25T12:32:58.136Z\",\n        \"createdDate\": \"2018-09-03T12:54:58.303Z\"\n    },\n    {\n        \"Code\": \"12\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Balqa\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-07-29T09:44:56.315Z\",\n        \"createdDate\": \"2018-09-03T12:54:58.303Z\"\n    },\n    {\n        \"Code\": \"32\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Tafilah\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-11-25T12:18:56.791Z\",\n        \"createdDate\": \"2018-09-03T12:54:58.303Z\"\n    },\n    {\n        \"Code\": \"33\",\n        \"DescriptionArabic\": \"????????\",\n        \"DescriptionEnglish\": \"Ma'an\",\n        \"Description\": \"????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-11-25T12:33:01.874Z\",\n        \"createdDate\": \"2018-09-03T12:54:58.303Z\"\n    },\n    {\n        \"Code\": \"24\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"Ajloun\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-12-20T15:07:35.075Z\",\n        \"createdDate\": \"2018-09-03T12:54:58.303Z\"\n    },\n    {\n        \"Code\": \"31\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"Karak\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-11-25T10:54:59.389Z\",\n        \"createdDate\": \"2018-09-03T12:54:58.303Z\"\n    },\n    {\n        \"Code\": \"34\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"Aqaba\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-19T07:44:35.961Z\",\n        \"createdDate\": \"2018-09-03T12:54:58.303Z\"\n    }\n]"
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
					"body": "[\n    {\n        \"Code\": \"201\",\n        \"HasEmployee\": false,\n        \"HasManager\": false,\n        \"DepartmentType\": \"CSPD_Office\",\n        \"MainOfficeInd\": false,\n        \"PrintingInd\": true,\n        \"AddressDetails\": \"??????????   ?????????? 05554921\",\n        \"AdditionalServiceFees\": 0,\n        \"ArabicIssuanceAuthority\": \"??????????\",\n        \"EnglishIssuanceAuthority\": \"AL SALT\",\n        \"PrintingExport\": \"1\",\n        \"DepartmentTypeExport\": \"1\",\n        \"EmbassyCode\": \"201\",\n        \"OnlineInd\": false,\n        \"CivilOfficeInd\": true,\n        \"InternalOffice\": false,\n        \"PrintingButton\": \"ViewAndPrinting\",\n        \"PassportFileInd\": true,\n        \"CheckIPAddress\": false,\n        \"embassyInd\": false,\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"AL SALT\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-12-27T16:09:42.077Z\",\n        \"createdDate\": \"2018-09-05T19:26:56.329Z\"\n    },\n    {\n        \"Code\": \"701\",\n        \"HasEmployee\": false,\n        \"HasManager\": false,\n        \"DepartmentType\": \"CSPD_Office\",\n        \"MainOfficeInd\": false,\n        \"PrintingInd\": true,\n        \"AddressDetails\": \"??????????????   ?????????? 03341116\",\n        \"AdditionalServiceFees\": 0,\n        \"ArabicIssuanceAuthority\": \"??????????????\",\n        \"EnglishIssuanceAuthority\": \"AL TAFILA\",\n        \"PrintingExport\": \"1\",\n        \"DepartmentTypeExport\": \"1\",\n        \"EmbassyCode\": \"701\",\n        \"OnlineInd\": false,\n        \"CivilOfficeInd\": true,\n        \"InternalOffice\": false,\n        \"PrintingButton\": \"ViewAndPrinting\",\n        \"PassportFileInd\": true,\n        \"CheckIPAddress\": false,\n        \"embassyInd\": false,\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"AL TAFILA\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-12-27T16:09:45.428Z\",\n        \"createdDate\": \"2018-09-05T19:26:56.329Z\"\n    },\n    {\n        \"Code\": \"601\",\n        \"HasEmployee\": false,\n        \"HasManager\": false,\n        \"DepartmentType\": \"CSPD_Office\",\n        \"MainOfficeInd\": true,\n        \"PrintingInd\": true,\n        \"AddressDetails\": \"????????????    ?????????? 03313864\",\n        \"AdditionalServiceFees\": 0,\n        \"ArabicIssuanceAuthority\": \"????????????\",\n        \"EnglishIssuanceAuthority\": \"AL AQABA\",\n        \"PrintingExport\": \"1\",\n        \"DepartmentTypeExport\": \"1\",\n        \"EmbassyCode\": \"601\",\n        \"OnlineInd\": false,\n        \"CivilOfficeInd\": true,\n        \"InternalOffice\": true,\n        \"PrintingButton\": \"Printing\",\n        \"PassportFileInd\": true,\n        \"CheckIPAddress\": false,\n        \"embassyInd\": false,\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"AL AQABA\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-09-06T14:29:59.316Z\",\n        \"createdDate\": \"2018-09-05T19:26:56.334Z\"\n    },\n    {\n        \"Code\": \"001\",\n        \"HasEmployee\": false,\n        \"HasManager\": false,\n        \"DepartmentType\": \"CSPD_Office\",\n        \"MainOfficeInd\": false,\n        \"PrintingInd\": true,\n        \"AddressDetails\": \"?????? ???????? / ???????????? ??????????    ??????????  636370\",\n        \"AdditionalServiceFees\": 0,\n        \"ArabicIssuanceAuthority\": \"???????? ??????????????\",\n        \"EnglishIssuanceAuthority\": \"AMMAN\",\n        \"PrintingExport\": \"1\",\n        \"DepartmentTypeExport\": \"1\",\n        \"EmbassyCode\": \"001\",\n        \"OnlineInd\": false,\n        \"CivilOfficeInd\": true,\n        \"InternalOffice\": false,\n        \"PrintingButton\": \"Printing\",\n        \"PassportFileInd\": true,\n        \"CheckIPAddress\": false,\n        \"embassyInd\": false,\n        \"DescriptionArabic\": \"???????? ??????????????\",\n        \"DescriptionEnglish\": \"AMMAN\",\n        \"Description\": \"???????? ??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-02-17T13:14:35.204Z\",\n        \"createdDate\": \"2018-09-05T19:26:56.334Z\"\n    },\n    {\n        \"Code\": \"003\",\n        \"HasEmployee\": false,\n        \"HasManager\": false,\n        \"DepartmentType\": \"CSPD_Office\",\n        \"MainOfficeInd\": false,\n        \"PrintingInd\": true,\n        \"AddressDetails\": \"???????? / ????????????   ??????????    4882968\",\n        \"AdditionalServiceFees\": 0,\n        \"ArabicIssuanceAuthority\": \"??????????\",\n        \"EnglishIssuanceAuthority\": \"MARKA\",\n        \"PrintingExport\": \"1\",\n        \"DepartmentTypeExport\": \"1\",\n        \"EmbassyCode\": \"003\",\n        \"OnlineInd\": false,\n        \"CivilOfficeInd\": true,\n        \"InternalOffice\": false,\n        \"PrintingButton\": \"Printing\",\n        \"PassportFileInd\": true,\n        \"CheckIPAddress\": false,\n        \"embassyInd\": false,\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"MARKA\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-02-17T13:14:33.626Z\",\n        \"createdDate\": \"2018-09-05T19:26:56.334Z\"\n    },\n    {\n        \"Code\": \"005\",\n        \"HasEmployee\": false,\n        \"HasManager\": false,\n        \"DepartmentType\": \"CSPD_Office\",\n        \"MainOfficeInd\": false,\n        \"PrintingInd\": true,\n        \"AddressDetails\": \"??????????   ??????????  5357428\",\n        \"AdditionalServiceFees\": 0,\n        \"ArabicIssuanceAuthority\": \"??????????\",\n        \"EnglishIssuanceAuthority\": \"SWEILEH\",\n        \"PrintingExport\": \"1\",\n        \"DepartmentTypeExport\": \"1\",\n        \"EmbassyCode\": \"005\",\n        \"OnlineInd\": false,\n        \"CivilOfficeInd\": true,\n        \"InternalOffice\": true,\n        \"PrintingButton\": \"Printing\",\n        \"PassportFileInd\": true,\n        \"CheckIPAddress\": false,\n        \"embassyInd\": false,\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"SWEILEH\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-03-24T06:19:58.063Z\",\n        \"createdDate\": \"2018-09-05T19:26:56.334Z\"\n    },\n    {\n        \"Code\": \"101\",\n        \"HasEmployee\": false,\n        \"HasManager\": false,\n        \"DepartmentType\": \"CSPD_Office\",\n        \"MainOfficeInd\": false,\n        \"PrintingInd\": true,\n        \"AddressDetails\": \"??????????????   ?????????? 09983821\",\n        \"AdditionalServiceFees\": 0,\n        \"ArabicIssuanceAuthority\": \"??????????????\",\n        \"EnglishIssuanceAuthority\": \"ZARQA\",\n        \"PrintingExport\": \"1\",\n        \"DepartmentTypeExport\": \"1\",\n        \"EmbassyCode\": \"101\",\n        \"OnlineInd\": false,\n        \"CivilOfficeInd\": true,\n        \"InternalOffice\": false,\n        \"PrintingButton\": \"ViewAndPrinting\",\n        \"PassportFileInd\": true,\n        \"CheckIPAddress\": false,\n        \"embassyInd\": false,\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"ZARQA\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-03-08T11:09:18.989Z\",\n        \"createdDate\": \"2018-09-05T19:26:56.334Z\"\n    },\n    {\n        \"Code\": \"009\",\n        \"HasEmployee\": false,\n        \"HasManager\": false,\n        \"DepartmentType\": \"CSPD_Office\",\n        \"MainOfficeInd\": false,\n        \"PrintingInd\": true,\n        \"AddressDetails\": \"????????    ?????????? 721175\",\n        \"AdditionalServiceFees\": 0,\n        \"ArabicIssuanceAuthority\": \"????????\",\n        \"EnglishIssuanceAuthority\": \"SAHAB\",\n        \"PrintingExport\": \"1\",\n        \"DepartmentTypeExport\": \"1\",\n        \"EmbassyCode\": \"009\",\n        \"OnlineInd\": false,\n        \"CivilOfficeInd\": true,\n        \"InternalOffice\": false,\n        \"PrintingButton\": \"ViewAndPrinting\",\n        \"PassportFileInd\": true,\n        \"CheckIPAddress\": false,\n        \"embassyInd\": false,\n        \"DescriptionArabic\": \"????????\",\n        \"DescriptionEnglish\": \"SAHAB\",\n        \"Description\": \"????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-09-02T13:30:06.110Z\",\n        \"createdDate\": \"2018-09-05T19:26:56.334Z\"\n    },\n    {\n        \"Code\": \"006\",\n        \"HasEmployee\": false,\n        \"HasManager\": false,\n        \"DepartmentType\": \"CSPD_Office\",\n        \"IP_Address_From\": \"10.69.10.70\",\n        \"MainOfficeInd\": false,\n        \"PrintingInd\": true,\n        \"AddressDetails\": \"?????? ????????????/????????   ?????????? 4610278\",\n        \"AdditionalServiceFees\": 0,\n        \"IP_Address_To\": \"10.69.10.76\",\n        \"ArabicIssuanceAuthority\": \"?????? ????????????\",\n        \"EnglishIssuanceAuthority\": \"JABAL ALHUSSEIN\",\n        \"PrintingExport\": \"1\",\n        \"DepartmentTypeExport\": \"1\",\n        \"EmbassyCode\": \"004\",\n        \"OnlineInd\": false,\n        \"CivilOfficeInd\": true,\n        \"InternalOffice\": false,\n        \"PrintingButton\": \"ViewAndPrinting\",\n        \"PassportFileInd\": false,\n        \"CheckIPAddress\": false,\n        \"embassyInd\": false,\n        \"DescriptionArabic\": \"?????? ????????????\",\n        \"DescriptionEnglish\": \"JABAL ALHUSSEIN\",\n        \"Description\": \"?????? ????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-03-21T09:23:20.741Z\",\n        \"createdDate\": \"2018-09-05T19:26:56.335Z\"\n    },\n    {\n        \"Code\": \"004\",\n        \"HasEmployee\": false,\n        \"HasManager\": false,\n        \"DepartmentType\": \"CSPD_Office\",\n        \"MainOfficeInd\": true,\n        \"PrintingInd\": true,\n        \"AddressDetails\": \"???????? ??????????   ??????????  814407\",\n        \"AdditionalServiceFees\": 0,\n        \"ArabicIssuanceAuthority\": \"???????? ?????????? \",\n        \"EnglishIssuanceAuthority\": \"wadi alsir\",\n        \"PrintingExport\": \"1\",\n        \"DepartmentTypeExport\": \"1\",\n        \"EmbassyCode\": \"005\",\n        \"OnlineInd\": false,\n        \"CivilOfficeInd\": true,\n        \"InternalOffice\": false,\n        \"PrintingButton\": \"Printing\",\n        \"PassportFileInd\": true,\n        \"CheckIPAddress\": false,\n        \"embassyInd\": false,\n        \"DescriptionArabic\": \"???????? ??????????\",\n        \"DescriptionEnglish\": \"WADI ALSIR\",\n        \"Description\": \"???????? ??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-02-17T13:14:36.313Z\",\n        \"createdDate\": \"2018-09-05T19:26:56.335Z\"\n    },\n    {\n        \"Code\": \"002\",\n        \"HasEmployee\": false,\n        \"HasManager\": false,\n        \"DepartmentType\": \"CSPD_Office\",\n        \"MainOfficeInd\": false,\n        \"PrintingInd\": true,\n        \"AddressDetails\": \"???????? / ???????? ?????????? ????????????   ?????????? 4754932\",\n        \"AdditionalServiceFees\": 0,\n        \"ArabicIssuanceAuthority\": \"????????????????\",\n        \"EnglishIssuanceAuthority\": \"AL ASHRAFEA\",\n        \"PrintingExport\": \"1\",\n        \"DepartmentTypeExport\": \"1\",\n        \"EmbassyCode\": \"002\",\n        \"OnlineInd\": false,\n        \"CivilOfficeInd\": true,\n        \"InternalOffice\": false,\n        \"PrintingButton\": \"Printing\",\n        \"PassportFileInd\": false,\n        \"CheckIPAddress\": false,\n        \"embassyInd\": false,\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"AL ASHRAFEA\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-01-11T10:50:38.384Z\",\n        \"createdDate\": \"2018-09-05T19:26:56.335Z\"\n    },\n    {\n        \"Code\": \"008\",\n        \"HasEmployee\": false,\n        \"HasManager\": false,\n        \"DepartmentType\": \"CSPD_Office\",\n        \"MainOfficeInd\": false,\n        \"PrintingInd\": true,\n        \"AddressDetails\": \"????????????   ?????????? 08560138\",\n        \"AdditionalServiceFees\": 0,\n        \"ArabicIssuanceAuthority\": \"????????????\",\n        \"EnglishIssuanceAuthority\": \"AL JEZA\",\n        \"PrintingExport\": \"1\",\n        \"DepartmentTypeExport\": \"1\",\n        \"EmbassyCode\": \"008\",\n        \"OnlineInd\": true,\n        \"CivilOfficeInd\": true,\n        \"InternalOffice\": true,\n        \"PrintingButton\": \"Printing\",\n        \"PassportFileInd\": true,\n        \"CheckIPAddress\": false,\n        \"embassyInd\": false,\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"AL JEZA\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-12-27T16:23:41.158Z\",\n        \"createdDate\": \"2018-09-05T19:26:56.336Z\"\n    },\n    {\n        \"Code\": \"904\",\n        \"HasEmployee\": false,\n        \"HasManager\": false,\n        \"DepartmentType\": \"CSPD_Office\",\n        \"MainOfficeInd\": false,\n        \"PrintingInd\": false,\n        \"AddressDetails\": \"????????????    ?????????? 03313864\",\n        \"AdditionalServiceFees\": 0,\n        \"ArabicIssuanceAuthority\": \"????????????\",\n        \"EnglishIssuanceAuthority\": \"AQABA\",\n        \"PrintingExport\": \"1\",\n        \"DepartmentTypeExport\": \"1\",\n        \"EmbassyCode\": \"904\",\n        \"OnlineInd\": false,\n        \"CivilOfficeInd\": true,\n        \"InternalOffice\": false,\n        \"PrintingButton\": \"Printing\",\n        \"PassportFileInd\": false,\n        \"CheckIPAddress\": false,\n        \"embassyInd\": false,\n        \"DescriptionArabic\": \"?????? / ????????????\",\n        \"DescriptionEnglish\": \" AQABA\",\n        \"Description\": \"?????? / ????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-02-17T14:45:38.004Z\",\n        \"createdDate\": \"2018-09-05T19:26:56.336Z\"\n    },\n    {\n        \"Code\": \"079\",\n        \"HasEmployee\": false,\n        \"HasManager\": false,\n        \"DepartmentType\": \"CSPD_Office\",\n        \"MainOfficeInd\": false,\n        \"PrintingInd\": true,\n        \"AddressDetails\": \"???????? ???? ???????????? ???????? ??????????\",\n        \"AdditionalServiceFees\": 0,\n        \"ArabicIssuanceAuthority\": \"???????? ??????????\",\n        \"EnglishIssuanceAuthority\": \"TILA ALALI\",\n        \"PrintingExport\": \"1\",\n        \"DepartmentTypeExport\": \"1\",\n        \"EmbassyCode\": \"079\",\n        \"OnlineInd\": false,\n        \"CivilOfficeInd\": true,\n        \"InternalOffice\": false,\n        \"PrintingButton\": \"Printing\",\n        \"PassportFileInd\": false,\n        \"CheckIPAddress\": false,\n        \"embassyInd\": false,\n        \"DescriptionArabic\": \"???????? ??????????\",\n        \"DescriptionEnglish\": \"TILA ALALI\",\n        \"Description\": \"???????? ??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-12-20T08:14:55.581Z\",\n        \"createdDate\": \"2018-09-05T19:26:56.337Z\"\n    },\n    {\n        \"Code\": \"018\",\n        \"HasEmployee\": false,\n        \"HasManager\": false,\n        \"DepartmentType\": \"CSPD_Office\",\n        \"MainOfficeInd\": true,\n        \"PrintingInd\": true,\n        \"AddressDetails\": \"????????????\",\n        \"AdditionalServiceFees\": 0,\n        \"ArabicIssuanceAuthority\": \"???????? ????????????\",\n        \"EnglishIssuanceAuthority\": \"AMMAN CENTER\",\n        \"PrintingExport\": \"1\",\n        \"DepartmentTypeExport\": \"1\",\n        \"EmbassyCode\": \"018\",\n        \"OnlineInd\": false,\n        \"CivilOfficeInd\": true,\n        \"InternalOffice\": false,\n        \"PrintingButton\": \"ViewAndPrinting\",\n        \"PassportFileInd\": true,\n        \"CheckIPAddress\": false,\n        \"embassyInd\": false,\n        \"DescriptionArabic\": \"???????? ????????????\",\n        \"DescriptionEnglish\": \"AMMAN CENTER\",\n        \"Description\": \"???????? ????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-02-17T13:14:35.735Z\",\n        \"createdDate\": \"2018-09-05T19:26:56.343Z\"\n    },\n    {\n        \"Code\": \"091\",\n        \"HasEmployee\": false,\n        \"HasManager\": false,\n        \"DepartmentType\": \"CSPD_Office\",\n        \"MainOfficeInd\": false,\n        \"PrintingInd\": false,\n        \"AddressDetails\": \"?????? ??????????\",\n        \"AdditionalServiceFees\": 0,\n        \"ArabicIssuanceAuthority\": \"????????\",\n        \"EnglishIssuanceAuthority\": \"amman\",\n        \"PrintingExport\": \"0\",\n        \"DepartmentTypeExport\": \"1\",\n        \"OnlineInd\": false,\n        \"CivilOfficeInd\": true,\n        \"InternalOffice\": false,\n        \"PrintingButton\": \"ViewAndPrinting\",\n        \"PassportFileInd\": false,\n        \"CheckIPAddress\": false,\n        \"embassyInd\": false,\n        \"DescriptionArabic\": \"???????? ?????? ??????????\",\n        \"DescriptionEnglish\": \"amman\",\n        \"Description\": \"???????? ?????? ??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-08-09T07:45:05.107Z\",\n        \"createdDate\": \"2020-08-09T07:42:06.054Z\"\n    },\n    {\n        \"Code\": \"069\",\n        \"HasEmployee\": false,\n        \"HasManager\": false,\n        \"DepartmentType\": \"CSPD_Office\",\n        \"MainOfficeInd\": false,\n        \"PrintingInd\": true,\n        \"AddressDetails\": \"???? ???????? ?????????? ???????????? ??????????????????\",\n        \"AdditionalServiceFees\": 0,\n        \"ArabicIssuanceAuthority\": \"????????\",\n        \"EnglishIssuanceAuthority\": \"amman\",\n        \"PrintingExport\": \"1\",\n        \"DepartmentTypeExport\": \"1\",\n        \"OnlineInd\": false,\n        \"CivilOfficeInd\": true,\n        \"InternalOffice\": true,\n        \"PrintingButton\": \"ViewAndPrinting\",\n        \"PassportFileInd\": true,\n        \"CheckIPAddress\": false,\n        \"embassyInd\": false,\n        \"DescriptionArabic\": \"???? ???????? \",\n        \"DescriptionEnglish\": \"hai nzaal \",\n        \"Description\": \"???? ???????? \",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-06-20T08:58:59.084Z\",\n        \"createdDate\": \"2021-06-20T08:55:46.585Z\"\n    }\n]"
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
					"body": "[\n    {\n        \"ISO_Code\": \"675\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"????????\",\n        \"CurrencyValue\": 2.25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:45:29.492Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"NationalityEnu\": \"CYPRIOTE\",\n        \"DescriptionArabic\": \"????????\",\n        \"DescriptionEnglish\": \"Cyprus\",\n        \"Description\": \"????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:45:29.492Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.228Z\"\n    },\n    {\n        \"ISO_Code\": \"508\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"ANGOLIAN\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"Angola\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-11-28T09:50:37.922Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"729\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"NationalityEnu\": \"BHUTAN\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"Bhutan\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-12-11T08:04:12.261Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"540\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"?????? ???????? ????????????\",\n        \"NationalityEnu\": \"SAINT HELENIAN\",\n        \"DescriptionArabic\": \"?????? ???????? ????????????\",\n        \"DescriptionEnglish\": \"Saint Helena Islands\",\n        \"Description\": \"?????? ???????? ????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-11-28T12:04:33.637Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"652\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????????\",\n        \"NationalityEnu\": \"????????????????????\",\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"????????????????\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-03-08T09:39:58.629Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"830\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"NationalityEnu\": \"HAITIAN\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"Haiti\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-03-30T13:07:51.532Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"839\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"GRENADA\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Grenada\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"528\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"NationalityEnu\": \"BURUNDIAN\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"Burundi\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"897\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"?????? ??????????\",\n        \"NationalityEnu\": \"VIRGIN ISLANDS\",\n        \"DescriptionArabic\": \"?????? ??????????\",\n        \"DescriptionEnglish\": \"Virgin Islands\",\n        \"Description\": \"?????? ??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"993\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"MYANMARIAN\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Myanmar\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"322\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": true,\n        \"CurrencyName\": \"???????? ??????????????\",\n        \"CurrencyValue\": 3500,\n        \"LastCurrencyUpdate\": \"2018-09-18T19:03:25.403Z\",\n        \"PhoneCode\": \"961\",\n        \"RestrictedExport\": \"0\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"LEBANESE\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"Lebanon\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-03-26T13:40:52.202Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"995\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"ANDORRIAN\",\n        \"DescriptionArabic\": \"?????????? ????????????\",\n        \"DescriptionEnglish\": \"PRINCIPALITY OF ANDORRA\",\n        \"Description\": \"?????????? ????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-03-26T14:22:56.079Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"600\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"PhoneCode\": \"599\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????\",\n        \"NationalityEnu\": \"CURACAOI\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"CURACAO\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-12-12T08:33:35.977Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"907\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"ESTONIAN\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"estonia\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-02-19T14:44:35.540Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"852\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????\",\n        \"NationalityEnu\": \"BELIZE\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"Belize\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-03-24T11:35:54.782Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"736\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"?????????? ????????????????\",\n        \"CurrencyValue\": 3.5,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:46:49.868Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????????\",\n        \"NationalityEnu\": \"SINGAPORE\",\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"Singapore\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:46:49.868Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"672\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"NationalityEnu\": \"KOSOVO\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"kosovo\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"692\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"ALBANIAN\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Albania\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-01-18T14:34:24.318Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"800\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"?????????? ????????????\",\n        \"CurrencyValue\": 2.25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:45:05.629Z\",\n        \"PhoneCode\": \"1\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"AMERICAN\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"USA\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-05-27T08:42:19.526Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"644\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"NationalityEnu\": \"SWEDISH\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"Sweden\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"762\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????\",\n        \"NationalityEnu\": \"??????????\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"??????????\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"846\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"???????? ??????????\",\n        \"NationalityEnu\": \"SAINT LUCIA\",\n        \"DescriptionArabic\": \"???????? ??????????\",\n        \"DescriptionEnglish\": \"Saint Lucia\",\n        \"Description\": \"???????? ??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"532\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"NationalityEnu\": \"MALAWIAN\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"Malawi\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"715\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"?????????? ??????????????????\",\n        \"CurrencyValue\": 320,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:24:31.522Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????????\",\n        \"NationalityEnu\": \"PAKISTANI\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Pakistan\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-02-18T12:29:35.833Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"853\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????\",\n        \"NationalityEnu\": \"FIJIAN\",\n        \"DescriptionArabic\": \"?????? ????????\",\n        \"DescriptionEnglish\": \"Fiji Island\",\n        \"Description\": \"?????? ????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"733\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"NEPALESE\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"Nepal\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-12-17T11:03:39.100Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"665\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"????????\",\n        \"CurrencyValue\": 2.25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:19:44.308Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"GREEK\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Greece\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:19:44.308Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"642\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"PhoneCode\": \"45\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????\",\n        \"NationalityEnu\": \"DANISH\",\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"Denmark\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-11-28T08:52:27.275Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"511\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"???? ????????????\",\n        \"CurrencyValue\": 65,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:46:21.373Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"ETHIOPIAN\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Ethiopia\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:46:21.373Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"774\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"HEBRIDES\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Hebrides\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"502\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"NationalityEnu\": \"CHADI\",\n        \"DescriptionArabic\": \"????????\",\n        \"DescriptionEnglish\": \"Chad\",\n        \"Description\": \"????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"645\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"?????????? ??????????????\",\n        \"CurrencyValue\": 20,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:46:02.719Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"NORWEGIAN\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Norway\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:46:02.719Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"653\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????????????\",\n        \"NationalityEnu\": \"??????????????????????\",\n        \"DescriptionArabic\": \"??????????????????\",\n        \"DescriptionEnglish\": \"??????????????????\",\n        \"Description\": \"??????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"842\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"???????? ??????????\",\n        \"NationalityEnu\": \"???????? ??????????\",\n        \"DescriptionArabic\": \"???????? ??????????\",\n        \"DescriptionEnglish\": \"???????? ??????????\",\n        \"Description\": \"???????? ??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"342\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"???????? ??????????\",\n        \"CurrencyValue\": 25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:37:29.928Z\",\n        \"PhoneCode\": \"212\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"NationalityEnu\": \"MOROCCAN\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"Morocco\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:37:29.928Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"885\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????\",\n        \"NationalityEnu\": \"PARAGUAYAN\",\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"Baraguay\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"513\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"???????? ??????????\",\n        \"NationalityEnu\": \"IVORIAN\",\n        \"DescriptionArabic\": \"???????? ??????????\",\n        \"DescriptionEnglish\": \"Ivory Coast\",\n        \"Description\": \"???????? ??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"724\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"?????????? ????????????????\",\n        \"NationalityEnu\": \"KOREAN\",\n        \"DescriptionArabic\": \"?????????? ????????????????\",\n        \"DescriptionEnglish\": \"North Korea\",\n        \"Description\": \"?????????? ????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"728\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"CAMBODIAN\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Cambodia\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"996\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"NationalityEnu\": \"MADAGASCAR\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"Rep. of  Madagascar\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"827\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????????????\",\n        \"NationalityEnu\": \"DOMINICAN\",\n        \"DescriptionArabic\": \"????????????????????\",\n        \"DescriptionEnglish\": \"Dominican\",\n        \"Description\": \"????????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-12-12T08:33:35.962Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"888\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"???????????? ????????????????\",\n        \"NationalityEnu\": \"GUIANIAN\",\n        \"DescriptionArabic\": \"???????????? ????????????????\",\n        \"DescriptionEnglish\": \"French Guiana\",\n        \"Description\": \"???????????? ????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"655\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"SOVIET\",\n        \"DescriptionArabic\": \"?????????????? ????????????????\",\n        \"DescriptionEnglish\": \"Soviet\",\n        \"Description\": \"?????????????? ????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-03-17T19:33:47.114Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"893\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????\",\n        \"NationalityEnu\": \"BRUNEI\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"Brunei\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"832\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"NationalityEnu\": \"JAMAICAN\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"Jamaica\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"702\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"?????????? ??????????????\",\n        \"NationalityEnu\": \"GUINEAN\",\n        \"DescriptionArabic\": \"?????????? ??????????????\",\n        \"DescriptionEnglish\": \"New Guinea\",\n        \"Description\": \"?????????? ??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"722\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????\",\n        \"NationalityEnu\": \"TAIWANESE\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"Taiwan\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"666\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????\",\n        \"NationalityEnu\": \"SERBIA\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"SERBIA\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"828\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????????\",\n        \"NationalityEnu\": \"SALVADOR\",\n        \"DescriptionArabic\": \"??????????????????\",\n        \"DescriptionEnglish\": \"Salvador\",\n        \"Description\": \"??????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-12-12T13:41:37.833Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"527\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????????\",\n        \"NationalityEnu\": \"BOTSWANAN\",\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"Botswana\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"734\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"???? ????????????\",\n        \"CurrencyValue\": 260,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:39:55.170Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"JAPANESE\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Japan\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:39:55.170Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"771\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????\",\n        \"NationalityEnu\": \"????????\",\n        \"DescriptionArabic\": \"????????\",\n        \"DescriptionEnglish\": \"????????\",\n        \"Description\": \"????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"908\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"NationalityEnu\": \"RWANDA\",\n        \"DescriptionArabic\": \"?????????????? ????????????\",\n        \"DescriptionEnglish\": \"Republic of Rwanda\",\n        \"Description\": \"?????????????? ????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"721\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"???????? ????????\",\n        \"CurrencyValue\": 20,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:34:07.210Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"?????????? ??????????????\",\n        \"NationalityEnu\": \"CHINESE\",\n        \"DescriptionArabic\": \"?????????? ??????????????\",\n        \"DescriptionEnglish\": \"China\",\n        \"Description\": \"?????????? ??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-05-28T12:07:39.165Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"826\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????????\",\n        \"NationalityEnu\": \"COSTARICAN\",\n        \"DescriptionArabic\": \"??????????????????\",\n        \"DescriptionEnglish\": \"Costarica\",\n        \"Description\": \"??????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"343\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"PhoneCode\": \"222\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????????\",\n        \"NationalityEnu\": \"MAURITANIAN\",\n        \"DescriptionArabic\": \"??????????????????\",\n        \"DescriptionEnglish\": \"Mauritania\",\n        \"Description\": \"??????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"990\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"SLOVENIA\",\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"slovenia\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"680\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????????????\",\n        \"NationalityEnu\": \"CZECHOSLOVAKIAN\",\n        \"DescriptionArabic\": \"??????????????????????????\",\n        \"DescriptionEnglish\": \"Czechoslovakia\",\n        \"Description\": \"??????????????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"737\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????\",\n        \"NationalityEnu\": \"MALDIVES\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"Maldives\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"731\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????\",\n        \"NationalityEnu\": \"VIETNAMESE\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"Vietnam\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"316\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"???????? ??????????\",\n        \"CurrencyValue\": 1,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:43:06.406Z\",\n        \"PhoneCode\": \"968\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"NationalityEnu\": \"OMANI\",\n        \"DescriptionArabic\": \"?????????? ????????\",\n        \"DescriptionEnglish\": \"Oman\",\n        \"Description\": \"?????????? ????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-06-15T09:26:25.965Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"825\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????????\",\n        \"NationalityEnu\": \"BARBADOS\",\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"Barbados\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"831\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????????\",\n        \"NationalityEnu\": \"HONDURASIA\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Honduras\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"514\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"NationalityEnu\": \"ZAMBIAN\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"Zambia\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"312\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"?????????? ??????????\",\n        \"CurrencyValue\": 0.7,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:41:11.961Z\",\n        \"PhoneCode\": \"965\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"NationalityEnu\": \"KUWAIT\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"Kuwait\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-11-25T08:44:44.266Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"670\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????????\",\n        \"NationalityEnu\": \"YUGOSLAVIAN\",\n        \"DescriptionArabic\": \"??????????????????\",\n        \"DescriptionEnglish\": \"Yugoslavia\",\n        \"Description\": \"??????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"636\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"PhoneCode\": \"378\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"?????? ????????\",\n        \"NationalityEnu\": \"SAN MARINO\",\n        \"DescriptionArabic\": \"?????? ????????????\",\n        \"DescriptionEnglish\": \"San Marino\",\n        \"Description\": \"?????? ????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"523\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????\",\n        \"NationalityEnu\": \"MALAGASY\",\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"Malagasy\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"542\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"?????? ??????????????\",\n        \"NationalityEnu\": \"SAOTOMEAN\",\n        \"DescriptionArabic\": \"?????? ??????????????\",\n        \"DescriptionEnglish\": \"Sao Tome and Pricipe\",\n        \"Description\": \"?????? ??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"535\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"?????? ??????????\",\n        \"NationalityEnu\": \"COMORAN\",\n        \"DescriptionArabic\": \"?????? ??????????\",\n        \"DescriptionEnglish\": \"Comoro Islands\",\n        \"Description\": \"?????? ??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"730\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"THAI\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"Thailand\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"310\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"???????? ??????????\",\n        \"CurrencyValue\": 9,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:35:46.312Z\",\n        \"PhoneCode\": \"966\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????\",\n        \"NationalityEnu\": \"SAUDIAN\",\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"Saudia Arabia\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-02-17T13:14:33.954Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"883\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"BOLIVIAN\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Bolivia\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"321\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": true,\n        \"CurrencyName\": \"???????? ??????????\",\n        \"CurrencyValue\": 1200,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:36:41.711Z\",\n        \"PhoneCode\": \"963\",\n        \"RestrictedExport\": \"0\",\n        \"NationalityAra\": \"??????????\",\n        \"NationalityEnu\": \"SYRIAN\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"Syria\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:36:41.711Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"516\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"SENEGALESE\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Sengal\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"778\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"?? ??????????\",\n        \"NationalityEnu\": \"?? ??????????\",\n        \"DescriptionArabic\": \"?? ??????????\",\n        \"DescriptionEnglish\": \"?? ??????????\",\n        \"Description\": \"?? ??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"848\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"???????? ????????????\",\n        \"NationalityEnu\": \"TURKS AND CAICOS\",\n        \"DescriptionArabic\": \"???????? ????????????\",\n        \"DescriptionEnglish\": \"Turks and Caicos\",\n        \"Description\": \"???????? ????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"650\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"????????\",\n        \"CurrencyValue\": 2.25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:30:11.407Z\",\n        \"PhoneCode\": \"49\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"GERMAN\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Germany\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:30:11.407Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"810\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"?????????? ????????\",\n        \"CurrencyValue\": 3.5,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:27:09.769Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????\",\n        \"NationalityEnu\": \"CANADIAN\",\n        \"DescriptionArabic\": \"????????\",\n        \"DescriptionEnglish\": \"Canada\",\n        \"Description\": \"????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:27:09.769Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"314\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"???????? ????????\",\n        \"CurrencyValue\": 9,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:36:52.226Z\",\n        \"PhoneCode\": \"974\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????\",\n        \"NationalityEnu\": \"QATARI\",\n        \"DescriptionArabic\": \"??????\",\n        \"DescriptionEnglish\": \"Qatar\",\n        \"Description\": \"??????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-09-20T10:45:13.613Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"651\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????\",\n        \"NationalityEnu\": \"BELARUS\",\n        \"DescriptionArabic\": \"?????????? ??????????????\",\n        \"DescriptionEnglish\": \"BELARUS\",\n        \"Description\": \"?????????? ??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"880\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????\",\n        \"NationalityEnu\": \"PERUSAL\",\n        \"DescriptionArabic\": \"????????\",\n        \"DescriptionEnglish\": \"Peru\",\n        \"Description\": \"????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"667\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????\",\n        \"NationalityEnu\": \"LITHUANIAN\",\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"Lithuania\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"525\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"PHILIPPINO\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Philippines\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"884\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????\",\n        \"NationalityEnu\": \"URUGUAYAN\",\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"Uruguay\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"350\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"???????? ????????????\",\n        \"CurrencyValue\": 110,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:36:19.881Z\",\n        \"PhoneCode\": \"249\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"SUDANESE\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Sudan\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:36:19.881Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"524\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"???????? ????????????\",\n        \"NationalityEnu\": \"BURKINABE\",\n        \"DescriptionArabic\": \"???????? ????????????\",\n        \"DescriptionEnglish\": \"Upper Volta\",\n        \"Description\": \"???????? ????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"001\",\n        \"CountryGroup\": \"Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"?????????? ??????????\",\n        \"PhoneCode\": \"962\",\n        \"RestrictedExport\": \"1\",\n        \"CurrencyNameEnu\": \"JOD\",\n        \"NationalityAra\": \"??????????\",\n        \"NationalityEnu\": \"JORDANIAN\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"JORDAN\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-03-21T09:23:20.749Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"763\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????????\",\n        \"NationalityEnu\": \"SOLOMON ISLAND\",\n        \"DescriptionArabic\": \"?????? ??????????????\",\n        \"DescriptionEnglish\": \"Solomon Island\",\n        \"Description\": \"?????? ??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"503\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????\",\n        \"NationalityEnu\": \"MALIAN\",\n        \"DescriptionArabic\": \"????????\",\n        \"DescriptionEnglish\": \"Mali\",\n        \"Description\": \"????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"887\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????\",\n        \"NationalityEnu\": \"FAULKLAND\",\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"Faulkland\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"719\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"???????????? ????????????\",\n        \"CurrencyValue\": 10,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:40:55.490Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"MALAYSIAN\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Malaysia\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:40:55.490Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"352\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"NationalityEnu\": \"ARETIRIAN\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"Aretiria\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-03-16T08:44:36.156Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"648\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"NationalityEnu\": \"MALTESE\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"Malta\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"112\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"PhoneCode\": \"220\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????\",\n        \"NationalityEnu\": \"GAMBIAN\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"GAMBIA\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"898\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????????\",\n        \"NationalityEnu\": \"SAINTLUCIA\",\n        \"DescriptionArabic\": \"??????????????????\",\n        \"DescriptionEnglish\": \"Saintlucia\",\n        \"Description\": \"??????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"699\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"NationalityEnu\": \"CORATIAN\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Croatia\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"773\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????\",\n        \"NationalityEnu\": \"GUINEAN\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"Guinea\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"890\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"NationalityEnu\": \"BOSNIAN HERZOGEVINIAN\",\n        \"DescriptionArabic\": \"?????????????? ??????????????\",\n        \"DescriptionEnglish\": \"Bosnia and Herzegovina\",\n        \"Description\": \"?????????????? ??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"506\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"UGANDANN\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"Uganda\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"835\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"BAHAMAS\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Bahamas\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-12-27T16:09:44.268Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"717\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"???????? ????????????\",\n        \"CurrencyValue\": 95000,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:39:41.240Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"IRANIAN\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"Iran\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-05-30T07:07:10.801Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"992\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????????\",\n        \"NationalityEnu\": \"LEICHTENSTEINIAN\",\n        \"DescriptionArabic\": \"??????????????????\",\n        \"DescriptionEnglish\": \"leichtenstein\",\n        \"Description\": \"??????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"889\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"UKRAINIAN\",\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"Ukraine\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"537\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"NAMIBIAN\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Namibia\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"317\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": true,\n        \"CurrencyName\": \"???????? ????????\",\n        \"CurrencyValue\": 600,\n        \"LastCurrencyUpdate\": \"2018-09-18T19:00:16.142Z\",\n        \"PhoneCode\": \"967\",\n        \"RestrictedExport\": \"0\",\n        \"NationalityAra\": \"??????????\",\n        \"NationalityEnu\": \"YEMENI\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"Yemen\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-18T19:00:16.142Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"881\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????\",\n        \"NationalityEnu\": \"COLOMBIAN\",\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"Colombia\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"663\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"MAKDONIAN\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Makdonia\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"739\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"???????? ????????\",\n        \"NationalityEnu\": \"HONG KONG\",\n        \"DescriptionArabic\": \"???????? ????????\",\n        \"DescriptionEnglish\": \"Hong Kong\",\n        \"Description\": \"???????? ????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"768\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"?? ??????????????\",\n        \"NationalityEnu\": \"?? ??????????????\",\n        \"DescriptionArabic\": \"?? ??????????????\",\n        \"DescriptionEnglish\": \"?? ??????????????\",\n        \"Description\": \"?? ??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"991\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"KYRGYZIAN\",\n        \"DescriptionArabic\": \"?????????????? ??????????\",\n        \"DescriptionEnglish\": \"Kyrgyz Republic\",\n        \"Description\": \"?????????????? ??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"994\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????????\",\n        \"NationalityEnu\": \"KYRGYZSTAN\",\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"kyrgyzstan\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"340\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"?????????? ??????????\",\n        \"CurrencyValue\": 7,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:34:53.324Z\",\n        \"PhoneCode\": \"216\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"NationalityEnu\": \"TUNISIAN\",\n        \"DescriptionArabic\": \"????????\",\n        \"DescriptionEnglish\": \"Tunisia\",\n        \"Description\": \"????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:34:53.324Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"510\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"ZAIRIAN\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"Zaire\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"776\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"?? ????????????????\",\n        \"NationalityEnu\": \"?? ????????????????\",\n        \"DescriptionArabic\": \"?? ????????????????\",\n        \"DescriptionEnglish\": \"?? ????????????????\",\n        \"Description\": \"?? ????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"531\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"TAILAND\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"TAILAND\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"876\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"???????? ??????????????\",\n        \"CurrencyValue\": 4,\n        \"PhoneCode\": \"962\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"?? ??????\",\n        \"NationalityEnu\": \"?? ??????\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"test\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-08-30T07:29:23.137Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"850\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"???????? ??????????????\",\n        \"CurrencyValue\": 9,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:29:54.743Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????\",\n        \"NationalityEnu\": \"BRAZILIAN\",\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"Brazil\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:29:54.743Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"683\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????\",\n        \"NationalityEnu\": \"CZECH\",\n        \"DescriptionArabic\": \"????????\",\n        \"DescriptionEnglish\": \"Czech\",\n        \"Description\": \"????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"685\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"POLISH\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Poland\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"860\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????\",\n        \"NationalityEnu\": \"VENEZUELIAN\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Venezuela\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"740\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????\",\n        \"NationalityEnu\": \"MACAU\",\n        \"DescriptionArabic\": \"????????\",\n        \"DescriptionEnglish\": \"Macau\",\n        \"Description\": \"????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"512\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????\",\n        \"NationalityEnu\": \"GHANAIAN\",\n        \"DescriptionArabic\": \"????????\",\n        \"DescriptionEnglish\": \"Ghana\",\n        \"Description\": \"????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"843\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"??????????????\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"??????????????\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"643\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"???????? ????????????\",\n        \"CurrencyValue\": 3,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:34:17.187Z\",\n        \"PhoneCode\": \"41\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"SWISS\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"SwitzerLand\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:34:17.187Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"820\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"?????????? ????????????\",\n        \"CurrencyValue\": 2.25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:43:16.604Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"MEXICAN\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Mexico\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:43:16.604Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"662\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"?????????? ????????????\",\n        \"CurrencyValue\": 2.25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:44:10.147Z\",\n        \"PhoneCode\": \"006\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????\",\n        \"NationalityEnu\": \"RUSSIAN\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"Russia\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-03-08T12:20:17.710Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"899\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"NationalityEnu\": \"BENIN\",\n        \"DescriptionArabic\": \"????????\",\n        \"DescriptionEnglish\": \"Benin\",\n        \"Description\": \"????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"701\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"?????????? ??????????\",\n        \"CurrencyValue\": 160,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:44:25.029Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????\",\n        \"NationalityEnu\": \"INDIAN\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"India\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:44:25.029Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"718\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"?????????? ??????????????????\",\n        \"CurrencyValue\": 33000,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:35:29.299Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????????\",\n        \"NationalityEnu\": \"ANDONISIAN\",\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"Indonesia\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:35:29.299Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"723\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????\",\n        \"NationalityEnu\": \"SRILANKAN\",\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"Sri Lanka\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"630\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"????????\",\n        \"CurrencyValue\": 2.25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:37:56.656Z\",\n        \"PhoneCode\": \"39\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"ITALIAN\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Italy\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:37:56.656Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"320\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"?????????? ????????????\",\n        \"CurrencyValue\": 2.25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:23:05.444Z\",\n        \"PhoneCode\": \"964\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"NationalityEnu\": \"IRAQI\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"Iraq\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:23:05.444Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"833\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????????\",\n        \"NationalityEnu\": \"SURINAM\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Surinam\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"741\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????\",\n        \"NationalityEnu\": \"??????????\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"??????????\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"815\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????\",\n        \"NationalityEnu\": \"GREENLANDAR\",\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"Greenland\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"637\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"NationalityEnu\": \"MONACO\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"Monaco\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"313\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"???????? ??????????????\",\n        \"CurrencyValue\": 9,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:36:31.817Z\",\n        \"PhoneCode\": \"971\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????\",\n        \"NationalityEnu\": \"EMIRATE\",\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"UAE\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-03-08T11:09:18.966Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"331\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": true,\n        \"CurrencyName\": \"?????????? ????????\",\n        \"CurrencyValue\": 5,\n        \"LastCurrencyUpdate\": \"2018-09-18T19:02:41.667Z\",\n        \"PhoneCode\": \"218\",\n        \"RestrictedExport\": \"0\",\n        \"NationalityAra\": \"??????????\",\n        \"NationalityEnu\": \"LIBYAN\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"Libya\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-07-02T12:01:37.385Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"656\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"??????????\",\n        \"CurrencyValue\": 4,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:29:29.840Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????????\",\n        \"NationalityEnu\": \"AZERBAIJANI\",\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"Azerbaijan\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-06-09T07:37:48.502Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"765\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"NationalityEnu\": \"????????????\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"??????????\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"896\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????\",\n        \"NationalityEnu\": \"PORTUGESE\",\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"Portugal\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-06-27T13:02:47.921Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"891\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"?????????? ????????????\",\n        \"CurrencyValue\": 2.25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:39:25.930Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"UZBEKISTAN\",\n        \"DescriptionArabic\": \"????????????????????\",\n        \"DescriptionEnglish\": \"Uzbekistan\",\n        \"Description\": \"????????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-06-09T06:41:48.363Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"732\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"MANGOLLIAN\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Mangolla\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"906\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"???????? ???????? ????????????\",\n        \"CurrencyValue\": 35,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:33:32.990Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"???????? ??????????????\",\n        \"NationalityEnu\": \"SOUTH AFRICA\",\n        \"DescriptionArabic\": \"???????? ??????????????\",\n        \"DescriptionEnglish\": \"SOUTH AFRICA\",\n        \"Description\": \"???????? ??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:33:32.990Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"625\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"????????\",\n        \"CurrencyValue\": 2.25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:29:14.937Z\",\n        \"PhoneCode\": \"33\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"NationalityEnu\": \"FRENCH\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"France\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:29:14.937Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"529\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"?????????????? ????????????\",\n        \"NationalityEnu\": \"CENTRAI AFRICA\",\n        \"DescriptionArabic\": \"?????????????? ????????????\",\n        \"DescriptionEnglish\": \"Central Africa\",\n        \"Description\": \"?????????????? ????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-03-15T10:52:43.385Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"851\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????\",\n        \"NationalityEnu\": \"GUYANA\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"guyana\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"509\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????????\",\n        \"NationalityEnu\": \"ZIMBABWE\",\n        \"DescriptionArabic\": \"??????????????????\",\n        \"DescriptionEnglish\": \"Zimbabwe\",\n        \"Description\": \"??????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"330\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"???????? ????????\",\n        \"CurrencyValue\": 40,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:40:19.490Z\",\n        \"PhoneCode\": \"962\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????\",\n        \"NationalityEnu\": \"EGYPTIaaaN\",\n        \"DescriptionArabic\": \"??????\",\n        \"DescriptionEnglish\": \"Egypt\",\n        \"Description\": \"??????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-09-29T07:38:12.658Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"767\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????????\",\n        \"NationalityEnu\": \"??????????????????\",\n        \"DescriptionArabic\": \"??????????????????\",\n        \"DescriptionEnglish\": \"??????????????????\",\n        \"Description\": \"??????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"902\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"CHECHENIA\",\n        \"DescriptionArabic\": \"?????????????? ??????????????\",\n        \"DescriptionEnglish\": \"Chechian\",\n        \"Description\": \"?????????????? ??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"355\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"PhoneCode\": \"211\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"???????? ??????????????\",\n        \"NationalityEnu\": \"SOUTH SUDAN\",\n        \"DescriptionArabic\": \"???????? ??????????????\",\n        \"DescriptionEnglish\": \"South Sudan\",\n        \"Description\": \"???????? ??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"837\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"BELIZEAN\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"BELIZE\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"635\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"????????\",\n        \"CurrencyValue\": 2.25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:42:54.530Z\",\n        \"PhoneCode\": \"34\",\n        \"RestrictedExport\": \"1\",\n        \"CurrencyNameEnu\": \"euro\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"SPANISH\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Spain\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-03-14T09:56:10.260Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"886\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"NationalityEnu\": \"????????????\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"????????????\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"003\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"???????? ????????????????\",\n        \"CurrencyValue\": 9,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:37:04.929Z\",\n        \"PhoneCode\": \"970\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"PALESTINIAN 48\",\n        \"DescriptionArabic\": \"???????????? 48\",\n        \"DescriptionEnglish\": \"Palestine\",\n        \"Description\": \"???????????? 48\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-03-24T13:39:50.671Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"000\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"???????? ????????????????\",\n        \"CurrencyValue\": 0.126,\n        \"LastCurrencyUpdate\": \"2021-09-14T11:28:29.870Z\",\n        \"PhoneCode\": \"972\",\n        \"RestrictedExport\": \"1\",\n        \"CurrencyNameEnu\": \"\",\n        \"NationalityAra\": \"????????????????\",\n        \"NationalityEnu\": \"ISRAELI\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Israel\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-09-14T11:28:29.870Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"903\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"NationalityEnu\": \"BOSNIAN\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Bosnia\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"905\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????\",\n        \"NationalityEnu\": \"DAGHESTANI\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Daghestan\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"664\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"NationalityEnu\": \"LATVIAN\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"Latvia\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"845\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"???????? ???????? ??????????\",\n        \"NationalityEnu\": \"SAINT KITTS AND NEVIS\",\n        \"DescriptionArabic\": \"???????? ???????? ??????????\",\n        \"DescriptionEnglish\": \"Saint Kitts and Nevis\",\n        \"Description\": \"???????? ???????? ??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"526\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"NationalityEnu\": \"DAHOMEY\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"Dahomey\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"892\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????????????\",\n        \"NationalityEnu\": \"BURKINA FASO\",\n        \"DescriptionArabic\": \"??????????????????????\",\n        \"DescriptionEnglish\": \"Burkina Faso\",\n        \"Description\": \"??????????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"822\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????????\",\n        \"NationalityEnu\": \"NICARAGUA\",\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"Nicaragua\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"501\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"PhoneCode\": \"234\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"NIGERIAN\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Nigeria\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"539\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"?????? ??????????\",\n        \"NationalityEnu\": \"?????? ??????????\",\n        \"DescriptionArabic\": \"?????? ??????????\",\n        \"DescriptionEnglish\": \"?????? ??????????\",\n        \"Description\": \"?????? ??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"769\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"NationalityEnu\": \"GUAM\",\n        \"DescriptionArabic\": \"????????\",\n        \"DescriptionEnglish\": \"Guam\",\n        \"Description\": \"????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"690\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"BULGARIAN\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Bulgaria\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"725\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"?????? ????????\",\n        \"CurrencyValue\": 2600,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:38:35.807Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"?????????? ????????????????\",\n        \"NationalityEnu\": \"SOUTH KOREA\",\n        \"DescriptionArabic\": \"?????????? ????????????????\",\n        \"DescriptionEnglish\": \"South Korea\",\n        \"Description\": \"?????????? ????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:38:35.807Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"522\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"CAMEROONIAN\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Cameroon\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-12-12T13:13:37.802Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"505\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"LIBERIAN\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Liberia\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"904\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"QARGEEZIAN\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Qargeezia\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"341\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"?????????? ????????????\",\n        \"CurrencyValue\": 350,\n        \"LastCurrencyUpdate\": \"2021-05-06T11:05:13.532Z\",\n        \"PhoneCode\": \"213\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"ALGERIAN\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Algeria\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-05-06T11:05:13.532Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"726\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????\",\n        \"NationalityEnu\": \"LAOTIAN\",\n        \"DescriptionArabic\": \"????????\",\n        \"DescriptionEnglish\": \"Laos\",\n        \"Description\": \"????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"681\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"NationalityEnu\": \"CZECH\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"Al Czech\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"775\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????\",\n        \"NationalityEnu\": \"NIUE\",\n        \"DescriptionArabic\": \"??????\",\n        \"DescriptionEnglish\": \"Niue\",\n        \"Description\": \"??????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"518\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"NIGERIAN\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"Niger\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"111\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyValue\": 150,\n        \"LastCurrencyUpdate\": \"2019-06-02T11:14:56.376Z\",\n        \"PhoneCode\": \"230\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????????\",\n        \"NationalityEnu\": \"MAURITIAN\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Mauritius\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-06-02T11:14:56.376Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"691\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"HUNGARIAN\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Hungary\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"735\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????\",\n        \"NationalityEnu\": \"??????????\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"??????????\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"761\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????\",\n        \"NationalityEnu\": \"SAMWA\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"Samwa\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"658\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????????\",\n        \"NationalityEnu\": \"TAGIK\",\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"Tajikistan\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"720\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"???????? ??????????\",\n        \"CurrencyValue\": 13,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:24:45.883Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????\",\n        \"NationalityEnu\": \"TURKISH\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"Turkey\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-01-06T11:29:41.381Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"654\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"ARMANIAN\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Armenia\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"764\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????\",\n        \"NationalityEnu\": \"????????\",\n        \"DescriptionArabic\": \"????????\",\n        \"DescriptionEnglish\": \"????????\",\n        \"Description\": \"????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"882\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"ECUADORAN\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Ecuador\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-12-17T13:02:43.987Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"849\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"???????? ??????????\",\n        \"NationalityEnu\": \"SINT MAARTEN\",\n        \"DescriptionArabic\": \"???????? ??????????\",\n        \"DescriptionEnglish\": \"Sint Maarten\",\n        \"Description\": \"???????? ??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"641\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"????????\",\n        \"CurrencyValue\": 2.25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:32:06.798Z\",\n        \"PhoneCode\": \"32\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"BELGIAN\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"Belgium\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:32:06.798Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"507\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"TANZANIAN\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Tanzania\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"682\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????\",\n        \"NationalityEnu\": \"SLOVAKIAN\",\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"Slovakia\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"900\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????????\",\n        \"NationalityEnu\": \"SCOTISH\",\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"Scotland\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-12-19T10:39:34.908Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"517\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????\",\n        \"NationalityEnu\": \"SEIRRALEONE\",\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"Seirraleone\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"870\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"?????????? ????????????\",\n        \"CurrencyValue\": 2.25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:38:21.368Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"NationalityEnu\": \"CHILEAN\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"Chile\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:38:21.368Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"844\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????????\",\n        \"NationalityEnu\": \"PUERTORICAN\",\n        \"DescriptionArabic\": \"??????????????????\",\n        \"DescriptionEnglish\": \"Puerto Rico\",\n        \"Description\": \"??????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.243Z\"\n    },\n    {\n        \"ISO_Code\": \"555\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"PhoneCode\": \"1-268\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"?????????????? ?? ??????????????\",\n        \"NationalityEnu\": \"ANTIGUAN AND BARBUDAN\",\n        \"DescriptionArabic\": \"?????????????? ?? ??????????????\",\n        \"DescriptionEnglish\": \"ANTIGUA AND BARBUDA\",\n        \"Description\": \"?????????????? ?? ??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"657\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"?????????? ????????????\",\n        \"CurrencyValue\": 2.25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:24:12.899Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????????\",\n        \"NationalityEnu\": \"KAZAKHISTAN\",\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"kazakhistan\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:24:12.899Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"533\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"POLISH\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"Poland\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"836\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????\",\n        \"NationalityEnu\": \"????????????????\",\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"????????????????\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"841\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????\",\n        \"NationalityEnu\": \"MARTINIQUE\",\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"Martinique\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"520\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????\",\n        \"NationalityEnu\": \"TOGOLESE\",\n        \"DescriptionArabic\": \"????????\",\n        \"DescriptionEnglish\": \"Togo\",\n        \"Description\": \"????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"631\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"PhoneCode\": \"379\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????????\",\n        \"NationalityEnu\": \"VATICAN\",\n        \"DescriptionArabic\": \"??????????????????\",\n        \"DescriptionEnglish\": \"Vatican City\",\n        \"Description\": \"??????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"649\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"LUXEMBURG\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Luxemburg\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"716\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"BANGLADESHI\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Bangladesh\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"536\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????????\",\n        \"NationalityEnu\": \"MOZAMBICAN\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Mozambigue\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"875\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????????\",\n        \"NationalityEnu\": \"ARGENTINIAN\",\n        \"DescriptionArabic\": \"??????????????????\",\n        \"DescriptionEnglish\": \"Argentina\",\n        \"Description\": \"??????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-03-18T10:59:35.983Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"546\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"???????????? ????????\",\n        \"CurrencyValue\": 1.5,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????????????\",\n        \"NationalityEnu\": \"LUXEMBOURG\",\n        \"DescriptionArabic\": \"??????????????????\",\n        \"DescriptionEnglish\": \"Luxembourg\",\n        \"Description\": \"??????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"504\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"???????????? ????????\",\n        \"CurrencyValue\": 230,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:45:48.294Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????\",\n        \"NationalityEnu\": \"KENYAN\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"Kenya\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:45:48.294Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"829\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????????\",\n        \"NationalityEnu\": \"GUATEMALAN\",\n        \"DescriptionArabic\": \"??????????????????\",\n        \"DescriptionEnglish\": \"Guatemala\",\n        \"Description\": \"??????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"750\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"?????????? ??????????????\",\n        \"CurrencyValue\": 3.5,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:40:34.430Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????\",\n        \"NationalityEnu\": \"AUSTRALIAN\",\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"Australia\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-03-14T09:08:54.187Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"530\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????\",\n        \"NationalityEnu\": \"CONGO\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"Congo\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"534\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"?????????????? ????????????????\",\n        \"NationalityEnu\": \"SOUTH AFRICA\",\n        \"DescriptionArabic\": \"?????????????? ????????????????\",\n        \"DescriptionEnglish\": \"South Africa\",\n        \"Description\": \"?????????????? ????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-12-12T09:15:44.133Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"772\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????????\",\n        \"NationalityEnu\": \"??????????????????\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"??????????????\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"640\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"????????\",\n        \"CurrencyValue\": 2.25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:40:10.031Z\",\n        \"PhoneCode\": \"43\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"AUSTRIAN\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"Austria\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:40:10.032Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"610\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"???????? ????????????????\",\n        \"CurrencyValue\": 2,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:42:23.523Z\",\n        \"PhoneCode\": \"44\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????\",\n        \"NationalityEnu\": \"BRITISH\",\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"UNITED KINGDOM\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:42:23.523Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"315\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"?????????? ????????????\",\n        \"CurrencyValue\": 1,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:43:58.772Z\",\n        \"PhoneCode\": \"973\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"BAHRAINI\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Bahrain\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2020-09-09T10:44:38.040Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"545\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"?????? ?????????? ????????????\",\n        \"NationalityEnu\": \"LABO CAMARINES NORTE\",\n        \"DescriptionArabic\": \"?????? ?????????? ????????????\",\n        \"DescriptionEnglish\": \"Labo Camarines Norte\",\n        \"Description\": \"?????? ?????????? ????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"727\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????\",\n        \"NationalityEnu\": \"BURMESE\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"Burma\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"541\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"?????? ????????\",\n        \"NationalityEnu\": \"SEYCHELLES\",\n        \"DescriptionArabic\": \"?????? ????????\",\n        \"DescriptionEnglish\": \"Seychelles\",\n        \"Description\": \"?????? ????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"351\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"PhoneCode\": \"252\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"SOMALI\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Somalia\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"824\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????/ ????????????\",\n        \"NationalityEnu\": \"TRINIDAD TOBAGO\",\n        \"DescriptionArabic\": \"????????????????/ ????????????\",\n        \"DescriptionEnglish\": \"Trinidad/Tobago\",\n        \"Description\": \"????????????????/ ????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"519\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????\",\n        \"NationalityEnu\": \"GUINEAN\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"Guinea\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"638\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"????????\",\n        \"CurrencyValue\": 1.5,\n        \"PhoneCode\": \"353\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????\",\n        \"NationalityEnu\": \"IRISH\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Ireland\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"620\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"????????\",\n        \"CurrencyValue\": 2.25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:42:09.963Z\",\n        \"PhoneCode\": \"31\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????\",\n        \"NationalityEnu\": \"DUTCH\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"NETHERLANDS\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:42:09.963Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"693\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????\",\n        \"NationalityEnu\": \"ALMAJAR\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"ALMAJAR\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"838\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"NationalityEnu\": \"????????????\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"????????????\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"840\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????\",\n        \"NationalityEnu\": \"GUADELOUPE\",\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"Guadeloupe\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"847\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"???????? ????????\",\n        \"NationalityEnu\": \"SAINT PRERRE\",\n        \"DescriptionArabic\": \"???????? ????????\",\n        \"DescriptionEnglish\": \"Saint Prerre\",\n        \"Description\": \"???????? ????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"639\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????\",\n        \"NationalityEnu\": \"ICELANDER\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"Iceland\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"742\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????\",\n        \"NationalityEnu\": \"??????????\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"??????????\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"901\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"????????\",\n        \"CurrencyValue\": 1.5,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????\",\n        \"NationalityEnu\": \"MOLDOVIAN\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Moldova\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"660\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"????????\",\n        \"CurrencyValue\": 2.25,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:29:43.376Z\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"ROMANIAN\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Romania\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2019-03-27T13:29:43.376Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"823\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????\",\n        \"NationalityEnu\": \"PANAMANIAN\",\n        \"DescriptionArabic\": \"????????\",\n        \"DescriptionEnglish\": \"Panama\",\n        \"Description\": \"????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"895\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????\",\n        \"NationalityEnu\": \"LITHUANIAN\",\n        \"DescriptionArabic\": \"????????????????\",\n        \"DescriptionEnglish\": \"Lithuania\",\n        \"Description\": \"????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"659\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"NationalityEnu\": \"GEORGIAN\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"Georgia\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"770\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"?? ????????????\",\n        \"NationalityEnu\": \"?? ????????????\",\n        \"DescriptionArabic\": \"?? ????????????\",\n        \"DescriptionEnglish\": \"?? ????????????\",\n        \"Description\": \"?? ????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"821\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????\",\n        \"NationalityEnu\": \"CUBAN\",\n        \"DescriptionArabic\": \"????????\",\n        \"DescriptionEnglish\": \"Cuba\",\n        \"Description\": \"????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"781\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????????????????\",\n        \"NationalityEnu\": \"WALLIS AND FUTUNA\",\n        \"DescriptionArabic\": \"??????????????????????????\",\n        \"DescriptionEnglish\": \"Wallis and Futuna\",\n        \"Description\": \"??????????????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"646\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"FINN\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"Finland\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"779\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????\",\n        \"NationalityEnu\": \"TONGA\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"Tonga\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"714\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????????????\",\n        \"NationalityEnu\": \"AFGHAN\",\n        \"DescriptionArabic\": \"??????????????????\",\n        \"DescriptionEnglish\": \"Afghanistan\",\n        \"Description\": \"??????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-03-15T09:14:38.784Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"002\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"???????? ????????????????\",\n        \"CurrencyValue\": 9,\n        \"LastCurrencyUpdate\": \"2019-03-27T13:37:09.040Z\",\n        \"PhoneCode\": \"970\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"PALESTINIAN\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"Palestine\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2022-02-28T07:40:09.147Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"353\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"PhoneCode\": \"253\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"DGIBOUTIAN\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"Djibouti\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"554\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"PhoneCode\": \"64\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????????\",\n        \"NationalityEnu\": \"NEW ZEALAND\",\n        \"DescriptionArabic\": \"??????????????????\",\n        \"DescriptionEnglish\": \"New Zealand\",\n        \"Description\": \"??????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"834\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"??????????????\",\n        \"DescriptionArabic\": \"????????????\",\n        \"DescriptionEnglish\": \"????????????\",\n        \"Description\": \"????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"661\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????????????????\",\n        \"NationalityEnu\": \"TURKMENISTANI\",\n        \"DescriptionArabic\": \"????????????????????\",\n        \"DescriptionEnglish\": \"Turkmenistan\",\n        \"Description\": \"????????????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"521\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????\",\n        \"NationalityEnu\": \"ZAMBIGUE\",\n        \"DescriptionArabic\": \"??????????\",\n        \"DescriptionEnglish\": \"zambigue\",\n        \"Description\": \"??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"515\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"??????????????\",\n        \"NationalityEnu\": \"NAMIBIAN\",\n        \"DescriptionArabic\": \"??????????????\",\n        \"DescriptionEnglish\": \"Namibia\",\n        \"Description\": \"??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2018-09-03T12:52:23.041Z\",\n        \"createdDate\": \"2018-09-03T12:52:22.259Z\"\n    },\n    {\n        \"ISO_Code\": \"Qui\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"Et aut deserunt nisi commodo libero\",\n        \"PhoneCode\": \"In volu\",\n        \"RestrictedExport\": \"1\",\n        \"CurrencyNameEnu\": \"Debitis non culpa temporibus cupiditate perspiciatis dolores\",\n        \"NationalityAra\": \"Minima ex ullamco commodi in id fugiat deserunt rerum sit saepe nesciunt vel dolores\",\n        \"NationalityEnu\": \"Laborum Quis aute aut tenetur quis quod corrupti cupiditate repudiandae ut qui quis voluptas eiusmod pariatur Fugit\",\n        \"DescriptionArabic\": \"?????????? ??????????????\",\n        \"DescriptionEnglish\": \"Ex aut adipisicing sit suscipit consectetur neque reprehenderit enim est eos et\",\n        \"Description\": \"?????????? ??????????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-09-14T11:06:59.128Z\",\n        \"createdDate\": \"2021-09-14T11:06:48.339Z\"\n    },\n    {\n        \"ISO_Code\": \"999\",\n        \"CountryGroup\": \"Non_Local\",\n        \"Restricted\": false,\n        \"CurrencyName\": \"??????????\",\n        \"PhoneCode\": \"962\",\n        \"RestrictedExport\": \"1\",\n        \"NationalityAra\": \"????????????\",\n        \"DescriptionArabic\": \"???????????? ??????????\",\n        \"DescriptionEnglish\": \"jordan s\",\n        \"Description\": \"???????????? ??????????\",\n        \"ActiveInd\": \"Active\",\n        \"changedDate\": \"2021-10-21T06:44:10.282Z\",\n        \"createdDate\": \"2021-10-21T06:43:10.491Z\"\n    }\n]"
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
					"body": "{\n    \"FirstName\": \"????????\",\n    \"SecondName\": \"????????\",\n    \"ThirdName\": \"????????\",\n    \"FamilyName\": \"??????????\",\n    \"Beneficiariess\": [\n        {\n            \"Name_Relation\": \"?????????? ???????? - ??????            \",\n            \"Nat_no\": \"9881005839\"\n        },\n        {\n            \"Name_Relation\": \"?????????? ???????? - ??????            \",\n            \"Nat_no\": \"9981054636\"\n        },\n        {\n            \"Name_Relation\": \"???????? ???????? - ???? ????????????      \",\n            \"Nat_no\": \"9551004578\"\n        },\n        {\n            \"Name_Relation\": \"???????? ?????????? - ????????           \",\n            \"Nat_no\": \"9642014055\"\n        },\n        {\n            \"Name_Relation\": \"???????? ???????? - ????????           \",\n            \"Nat_no\": \"9932028787\"\n        },\n        {\n            \"Name_Relation\": \"???????? ???????? - ????????           \",\n            \"Nat_no\": \"9902026301\"\n        }\n    ]\n}"
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
					"body": "{\n    \"FirstNameARA\": \"??????????\",\n    \"SecondNameARA\": \"????????\",\n    \"ThirdNameARA\": \"????????\",\n    \"FamilyNameARA\": \"??????????\",\n    \"FirstNameENU\": \"Jubran\",\n    \"SecondNameENU\": \"Fuad\",\n    \"ThirdNameENU\": \"Salem\",\n    \"FamilyNameENU\": \"Eisouh\",\n    \"Gender\": \"Male\",\n    \"NationalId\": \"9881005839\",\n    \"BirthDate\": \"1988-06-28T00:00:00.000Z\",\n    \"FFirstNameARA\": \"????????\",\n    \"FSecondNameARA\": \"????????\",\n    \"FFamilyNameARA\": \"??????????\",\n    \"MFirstNameARA\": \"????????\",\n    \"MSecondNameARA\": \"??????????\",\n    \"MFamilyNameARA\": \"????????\",\n    \"MFirstNameENU\": \"Wafa\",\n    \"FSecondNameENU\": \"Salem\",\n    \"FFamilyNameENU\": \"Eisouh\",\n    \"EnglishNameInd\": false,\n    \"CivilOffice\": \"??????????\",\n    \"CivilRegistrationNumber\": \"024/073\",\n    \"ReligionARA\": \"Christian\",\n    \"SerialNumber\": \"9881005839\",\n    \"FullName\": \"?????????? ???????? ???????? ??????????\",\n    \"PlaceOfBirthARA\": \"??????????\",\n    \"PlaceOfBirthENU\": \"AJLOUN\",\n    \"FatherReligionARA\": \"Christian\",\n    \"MotherReligionARA\": \"Christian\",\n    \"FatherReligionENU\": \"Christian\",\n    \"MotherReligionENU\": \"Christian\",\n    \"ReligionENU\": \"Christian\",\n    \"FFirstNameENU\": \"Fuad\",\n    \"WrittenDateARA\": \"???????????? ???????????????? ???? ???????????????????????? ???????? ?????? ???????????????? ?? ???????????? ?????????????? ????????????\",\n    \"WrittenDateENU\": \" Twenty Eighth OF June Nineteen Eighty Eight\",\n    \"CivilStatus\": \"Live\",\n    \"MSecondNameENU\": \"Yacoub\",\n    \"MFamilyNameENU\": \"Murad\",\n    \"ArNationality\": \"??????????\",\n    \"EnNationality\": \"JORDANIAN\",\n    \"EventNumber\": \"00040/000837\",\n    \"BirthRegisterType\": \"3\",\n    \"CheckDigit\": \"??\",\n    \"CivilOfficeENU\": \"AJLOUN\",\n    \"WantedInd\": false\n}"
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
				"description": "#### API endpoint to calculate the fees for the requested service .\n\n> A Successful API Request Will result in a??**HTTP 200**??status code .\n> \n> Request for non existing Applicant will return??**HTTP 400**??status code"
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
					"body": "{\n    \"Prerequisit\": \"<strong>?????????? ?????????? ?????????? ???????????? ???? ?????? ?????????? ?????????? ????????????</strong>\"\n}"
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
