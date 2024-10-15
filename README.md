📷 UnsplashAPITesting_Postman

Tested the Unsplash API using Postman, generated reports with Newman, and created detailed HTML reports using HTML Report Extra.

Unsplash API Documentation: https://unsplash.com/documentation#search-photos

📄 About

This project focuses on testing the Unsplash API to verify its functionality through automated requests using Postman. It includes comprehensive API tests covering user profiles, photos, collections, search, and statistics. Reports are generated with Newman and enhanced with HTML Report Extra for detailed insights into API performance.


🔧 Project Structure

Requests: 35 total requests across multiple endpoints.

Current User: 3 requests (Get Profile, Unauthorized Profile, Update Profile)

Users: 6 requests (Get Single User, Portfolio, List User Photos, Liked Photos, Collections, Stats)

Photos: 8 requests

Search: 3 requests

Collections: 9 requests

Topics: 3 requests

Stats: 2 requests

Authentication: 1 request

✅ Results Overview

Total Requests: 35

Failed Tests: 2

Skipped Tests: 0

Iterations: 1

🚀 Running the Tests

Clone the Repository:

git clone https://github.com/salwa1012/UnsplashAPITesting_Postman.git

Install Newman:

npm install -g newman

Run the Postman Collection:

newman run Unsplash\ API\ Testing.postman_collection.json -e UnsplashEnv.postman_environment.json

Generate HTML Report:

newman run Unsplash\ API\ Testing.postman_collection.json -e UnsplashEnv.postman_environment.json -r html --reporter-html-export report.html

📊 Test Scenarios

Current User: Profile retrieval, unauthorized access, profile update.

Users: View user portfolio, photos, collections, and statistics.

Photos: Search and retrieve photos.

Collections: Create, list, and manage photo collections.

Topics: Explore trending topics.

Stats: API usage statistics.
