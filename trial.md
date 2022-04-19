{
	"info": {
		"_postman_id": "38f18056-b495-4fc4-ad98-d55d77a92491",
		"name": "New Collection",
		"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json"
	},
	"item": [
		{
			"name": "countries",
			"request": {
				"method": "POST",
				"header": [],
				"url": {
					"raw": "http://localhost:8083/api/v2/test/countries",
					"protocol": "http",
					"host": [
						"localhost"
					],
					"port": "8083",
					"path": [
						"api",
						"v2",
						"test",
						"countries"
					]
				}
			},
			"response": []
		},
		{
			"name": "martial status",
			"request": {
				"method": "POST",
				"header": [],
				"url": {
					"raw": "http://localhost:8083/api/v2/test/martialstatus",
					"protocol": "http",
					"host": [
						"localhost"
					],
					"port": "8083",
					"path": [
						"api",
						"v2",
						"test",
						"martialstatus"
					]
				}
			},
			"response": []
		},
		{
			"name": "departments",
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
					"raw": "http://localhost:8083/api/v2/test/departments",
					"protocol": "http",
					"host": [
						"localhost"
					],
					"port": "8083",
					"path": [
						"api",
						"v2",
						"test",
						"departments"
					]
				}
			},
			"response": []
		},
		{
			"name": "cities",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\"ISO_Code\":\"001\"}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "http://localhost:8083/api/v2/test/cities",
					"protocol": "http",
					"host": [
						"localhost"
					],
					"port": "8083",
					"path": [
						"api",
						"v2",
						"test",
						"cities"
					]
				}
			},
			"response": []
		},
		{
			"name": "applicant",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\"NAT_NO\":\"1234\"}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "http://localhost:8083/api/v2/test/applicantes",
					"protocol": "http",
					"host": [
						"localhost"
					],
					"port": "8083",
					"path": [
						"api",
						"v2",
						"test",
						"applicantes"
					]
				}
			},
			"response": []
		},
		{
			"name": "Beneficiary",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\"NAT_NO\":\"00\"}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "http://localhost:8083/api/v2/test/beneficiaries",
					"protocol": "http",
					"host": [
						"localhost"
					],
					"port": "8083",
					"path": [
						"api",
						"v2",
						"test",
						"beneficiaries"
					]
				}
			},
			"response": []
		},
		{
			"name": "fees",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\r\n \"DeliveryCountryCode\":\"001\",\r\n \"ServiceType\":\"Birth_Certificate\",\r\n \"DeliveryType\":\"Aramex\",\r\n \"arabicCopies\":0,\r\n \"EnglishCopies\":1\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "http://localhost:8083/api/v2/test/fees",
					"protocol": "http",
					"host": [
						"localhost"
					],
					"port": "8083",
					"path": [
						"api",
						"v2",
						"test",
						"fees"
					]
				}
			},
			"response": []
		},
		{
			"name": "prerequiste",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\"ServiceType\":\"Birth_Certificate\",\r\n\"UserLanguage\":\"ar_JO\"}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "http://localhost:8083/api/v2/test/prerequisit",
					"protocol": "http",
					"host": [
						"localhost"
					],
					"port": "8083",
					"path": [
						"api",
						"v2",
						"test",
						"prerequisit"
					]
				}
			},
			"response": []
		},
		{
			"name": "english name",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\"ServiceType\":\"Birth_Certificate\",\r\n\"NAT_NO\":\"1234\"}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "http://localhost:8083/api/v2/test/englishname",
					"protocol": "http",
					"host": [
						"localhost"
					],
					"port": "8083",
					"path": [
						"api",
						"v2",
						"test",
						"englishname"
					]
				}
			},
			"response": []
		}
	]
}
