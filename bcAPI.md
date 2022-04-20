{
	"info": {
		"_postman_id": "0ced729f-636b-467f-983c-6f41f49cb257",
		"name": "New Collection",
		"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json"
	},
	"item": [
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
		}
	]
}
