{
	"info": {
		"_postman_id": "0ced729f-636b-467f-983c-6f41f49cb257",
		"name": "New Collection",
		"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json"
	},
	"item": [
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
		}
	]
}
