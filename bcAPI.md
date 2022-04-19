{
	"info": {
		"_postman_id": "b66543f5-3994-4c58-8169-f3d861ad0e19",
		"name": "Birth Certificate Service_v1 Copy 2",
		"description": "> This Collection Contain Sample requests for Birth_Certiicate_Service\n\nIt Contains the following requests:\n\n*   Get Applicant Data\n*   Get Beneficiary Birth Data\n*   Get Fees\n*   Get prerequisites\n*   Get List Of Countries\n*   Get List Of Martial Status\n*   Get List Of Cites\n*   Get List Of Departments",
		"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json"
	},
	"item": [
		{
			"name": "Get Martial Status",
			"request": {
				"method": "POST",
				"header": [
					{
						"key": "Access-Control-Allow-Origin",
						"value": "*",
						"type": "text"
					}
				],
				"url": {
					"raw": "http://localhost:8083/birthcertificate/martialstatus",
					"protocol": "http",
					"host": [
						"localhost"
					],
					"port": "8083",
					"path": [
						"birthcertificate",
						"martialstatus"
					]
				},
				"description": "API endpoint to **Get list of martial status** from the system .\n\n> A Successful API Request Will result in a **HTTP 200** status code ."
			},
			"response": []
		},
		{
			"name": "Get List Of City",
			"request": {
				"method": "POST",
				"header": [
					{
						"key": "Access-Control-Allow-Origin",
						"value": "*",
						"type": "text"
					}
				],
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
					"raw": "http://localhost:8083/birthcertificate/cities",
					"protocol": "http",
					"host": [
						"localhost"
					],
					"port": "8083",
					"path": [
						"birthcertificate",
						"cities"
					]
				},
				"description": "API endpoint to **Get list of Cities** in the system .\n\n> A Successful API Request Will result in a **HTTP 200** status code ."
			},
			"response": []
		},
		{
			"name": "Get List Of Countries",
			"request": {
				"method": "POST",
				"header": [
					{
						"key": "Access-Control-Allow-Origin",
						"value": "*",
						"type": "text"
					}
				],
				"url": {
					"raw": "http://localhost:8083/birthcertificate/countries",
					"protocol": "http",
					"host": [
						"localhost"
					],
					"port": "8083",
					"path": [
						"birthcertificate",
						"countries"
					]
				},
				"description": "API endpoint to **Get list of Countries** in the system .\n\n> A Successful API Request Will result in a **HTTP 200** status code ."
			},
			"response": []
		},
		{
			"name": "Get Applicant Data",
			"request": {
				"method": "POST",
				"header": [
					{
						"key": "Access-Control-Allow-Origin",
						"value": "*",
						"type": "text"
					}
				],
				"body": {
					"mode": "raw",
					"raw": "{\r\n    \"NAT_NO\": \"1234\"\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "http://localhost:8083/birthcertificate/applicantes",
					"protocol": "http",
					"host": [
						"localhost"
					],
					"port": "8083",
					"path": [
						"birthcertificate",
						"applicantes"
					]
				},
				"description": "API endpoint to **Fetch Data foer an applicant** in the system .\n\n> A Successful API Request Will result in a **HTTP 200** status code .\n> \n> Request for non existing Applicant will return **HTTP 400** status code"
			},
			"response": []
		},
		{
			"name": "Get Beneficiary Birth Data",
			"request": {
				"method": "POST",
				"header": [
					{
						"key": "Access-Control-Allow-Origin",
						"value": "*",
						"type": "text"
					}
				],
				"body": {
					"mode": "raw",
					"raw": "{\r\n    \"NAT_NO\": \"00\"\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "http://localhost:8083/birthcertificate/beneficiaries",
					"protocol": "http",
					"host": [
						"localhost"
					],
					"port": "8083",
					"path": [
						"birthcertificate",
						"beneficiaries"
					]
				},
				"description": "API endpoint to **Fetch The Birth Data for the applicant's beneficiery** in the system .\n\n> A Successful API Request Will result in a **HTTP 200** status code .\n> \n> Request for non existing Applicant will return **HTTP 400** status code"
			},
			"response": []
		},
		{
			"name": "Fees Calculation",
			"request": {
				"method": "POST",
				"header": [
					{
						"key": "Access-Control-Allow-Origin",
						"value": "*",
						"type": "text"
					}
				],
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
					"raw": "http://localhost:8083/birthcertificate/fees",
					"protocol": "http",
					"host": [
						"localhost"
					],
					"port": "8083",
					"path": [
						"birthcertificate",
						"fees"
					]
				},
				"description": "#### API endpoint to calculate the fees for the requested service .\n\n> A Successful API Request Will result in a **HTTP 200** status code .\n> \n> Request for non existing Applicant will return **HTTP 400** status code"
			},
			"response": []
		},
		{
			"name": "Get Prerequisit",
			"request": {
				"method": "POST",
				"header": [
					{
						"key": "Access-Control-Allow-Origin",
						"value": "*",
						"type": "text"
					}
				],
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
					"raw": "http://localhost:8083/birthcertificate/prerequisit",
					"protocol": "http",
					"host": [
						"localhost"
					],
					"port": "8083",
					"path": [
						"birthcertificate",
						"prerequisit"
					]
				},
				"description": "#### API endpoint to get the prerequisite for the requested service .\n\n> A Successful API Request Will result in a **HTTP 200** status code .\n> \n> Request for non existing Applicant will return **HTTP 400** status code"
			},
			"response": []
		},
		{
			"name": "Check English Name",
			"request": {
				"method": "POST",
				"header": [
					{
						"key": "Access-Control-Allow-Origin",
						"value": "*",
						"type": "text"
					}
				],
				"body": {
					"mode": "raw",
					"raw": "{\"NAT_NO\":\"1234\",\r\n\"ServiceType\":\"Birth_Certificate\"}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "http://localhost:8083/birthcertificate/englishname",
					"protocol": "http",
					"host": [
						"localhost"
					],
					"port": "8083",
					"path": [
						"birthcertificate",
						"englishname"
					]
				},
				"description": "#### API endpoint to check the editability for an English name for the input national number .\n\n> A Successful API Request Will result in a **HTTP 200** status code .\n> \n> Request for non existing Applicant will return **HTTP 400** status code"
			},
			"response": []
		}
	]
}
