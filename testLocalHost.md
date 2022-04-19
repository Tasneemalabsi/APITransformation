{
	"info": {
		"_postman_id": "bc8daf74-7ad3-4459-ae07-d07fff43ffb0",
		"name": "Birth Certificate Service_v2",
		"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json"
	},
	"item": [
		{
			"name": "New Request",
			"request": {
				"method": "POST",
				"header": [],
				"url": {
					"raw": "http://localhost:8083/api/v2/birthcertificate/countries",
					"protocol": "http",
					"host": [
						"localhost"
					],
					"port": "8083",
					"path": [
						"api",
						"v2",
						"birthcertificate",
						"countries"
					]
				}
			},
			"response": []
		},
		{
			"name": "Martial Status",
			"request": {
				"method": "POST",
				"header": [],
				"url": {
					"raw": "http://localhost:8083/api/v2/birthcertificate/martialstatus",
					"protocol": "http",
					"host": [
						"localhost"
					],
					"port": "8083",
					"path": [
						"api",
						"v2",
						"birthcertificate",
						"martialstatus"
					]
				}
			},
			"response": []
		},
		{
			"name": "Departments",
			"request": {
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
					"raw": "http://localhost:8083/api/v2/birthcertificate/departments",
					"protocol": "http",
					"host": [
						"localhost"
					],
					"port": "8083",
					"path": [
						"api",
						"v2",
						"birthcertificate",
						"departments"
					]
				}
			},
			"response": []
		},
		{
			"name": "Cities",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\r\n  \"ISO_Code\": \"001\"\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "http://localhost:8083/api/v2/birthcertificate/cities",
					"protocol": "http",
					"host": [
						"localhost"
					],
					"port": "8083",
					"path": [
						"api",
						"v2",
						"birthcertificate",
						"cities"
					]
				}
			},
			"response": []
		},
		{
			"name": "Applicant",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\r\n    \"NAT_NO\": \"5678\"\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "http://localhost:8083/api/v2/birthcertificate/applicantes",
					"protocol": "http",
					"host": [
						"localhost"
					],
					"port": "8083",
					"path": [
						"api",
						"v2",
						"birthcertificate",
						"applicantes"
					]
				}
			},
			"response": []
		},
		{
			"name": "Beneficary",
			"request": {
				"method": "POST",
				"header": [],
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
					"raw": "http://localhost:8083/api/v2/birthcertificate/beneficiaries",
					"protocol": "http",
					"host": [
						"localhost"
					],
					"port": "8083",
					"path": [
						"api",
						"v2",
						"birthcertificate",
						"beneficiaries"
					]
				}
			},
			"response": []
		},
		{
			"name": "Fees",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\r\n \"DeliveryCountryCode\":\"001\",\r\n \"ServiceType\":\"Birth_Certificate\",\r\n \"DeliveryType\":\"Aramex\",\r\n \"arabicCopies\":1,\r\n \"EnglishCopies\":1\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "http://localhost:8083/api/v2/birthcertificate/fees",
					"protocol": "http",
					"host": [
						"localhost"
					],
					"port": "8083",
					"path": [
						"api",
						"v2",
						"birthcertificate",
						"fees"
					]
				}
			},
			"response": []
		},
		{
			"name": "Prerequisit",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\r\n \"ServiceType\": \"Birth_Certificate\",\r\n \"UserLanguage\": \"en_US\"\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "http://localhost:8083/api/v2/birthcertificate/prerequisit",
					"protocol": "http",
					"host": [
						"localhost"
					],
					"port": "8083",
					"path": [
						"api",
						"v2",
						"birthcertificate",
						"prerequisit"
					]
				}
			},
			"response": []
		},
		{
			"name": "English Name",
			"request": {
				"method": "POST",
				"header": [],
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
					"raw": "http://localhost:8083/api/v2/birthcertificate/englishname",
					"protocol": "http",
					"host": [
						"localhost"
					],
					"port": "8083",
					"path": [
						"api",
						"v2",
						"birthcertificate",
						"englishname"
					]
				}
			},
			"response": []
		},
		{
			"name": "Submissions",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\r\n  \"AppliedBy\": \"Embassy\",\r\n  \"Nat_NO\": \"8\",\r\n  \"ISO_Code\": \"string\",\r\n  \"FirstName\": \"string\",\r\n  \"SecondName\": \"string\",\r\n  \"ThirdName\": \"string\",\r\n  \"FamilyName\": \"string\",\r\n  \"PhoneNumber\": \"string\",\r\n  \"EmailAddress\": \"string\",\r\n  \"BenificiaryNat_NO\": \"string\",\r\n  \"FullName\": \"string\",\r\n  \"Language\": \"Arabic\",\r\n  \"NumberOfCopiesAr\": 0,\r\n  \"NumberOfCopiesEn\": 0,\r\n  \"FirstNameENU\": \"string\",\r\n  \"SecondNameENU\": \"string\",\r\n  \"ThirdNameENU\": \"string\",\r\n  \"FamilyNameENU\": \"string\",\r\n  \"MFirstNameENU\": \"string\",\r\n  \"MSecondNameENU\": \"string\",\r\n  \"MFamilyNameENU\": \"string\",\r\n  \"PaymentType\": \"EFAWTEERcom\",\r\n  \"DeliveryType\": \"Aramex\",\r\n  \"RecipientName\": \"string\",\r\n  \"RecipientAddress\": \"string\",\r\n  \"StreetName\": \"string\",\r\n  \"RecipientMobile\": \"string\",\r\n  \"RecipientBuildingNO\": \"string\",\r\n  \"BenificiaryFullName\": \"string\",\r\n  \"FeeType\": \"string\",\r\n  \"CopiesNumber\": \"string\",\r\n  \"FeeAmount\": 0,\r\n  \"TotalFees\": 0,\r\n  \"CurrencyName\": \"string\"\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "http://localhost:8083/api/v2/birthcertificate/submissions",
					"protocol": "http",
					"host": [
						"localhost"
					],
					"port": "8083",
					"path": [
						"api",
						"v2",
						"birthcertificate",
						"submissions"
					]
				}
			},
			"response": []
		}
	]
}
