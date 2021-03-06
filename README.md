
# GithubUsersNotes

## Sample App of Nico Dioso

* Only iOS native API/Library were used
* Inconsistent pattern for view controllers were intended to show capability to write in different approach.
* 

### Sample app features:
1. Live API requests from Github.com
2. Persistent storing of loaded data (except images)
   - App will retain previously fetched data so when the app opens with no connection, app will show previously fetched data
3. Fetch pagination
4. Note adding to each user.
   - Works in offline mode, can still add notes to fetched users.
   - Notes added is searchable
5. Caching of Images
6. Connection Reachability detections.
   - If the app detects no connection, API requests are queued up. When the connection is restored, queued requests will automatically be executed.
7. Asynchronous API request
   - API requests does not happen simultaneously.
8. User filtering/searching
9. Basic Unit tests for CoreData managers and models
10. Works in Dark mode

![IMG_0882](https://user-images.githubusercontent.com/83448807/116686471-6c54c880-a9e6-11eb-91c8-6899fb84fa19.png)
![IMG_0880](https://user-images.githubusercontent.com/83448807/116681720-ea61a100-a9df-11eb-8189-9c140139ff85.png)
![IMG_0879](https://user-images.githubusercontent.com/83448807/116681737-f0578200-a9df-11eb-8e0b-e19c93acf82c.png)
