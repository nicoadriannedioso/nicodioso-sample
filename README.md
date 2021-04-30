# GithubUsersNotes

## Sample App of Nico Dioso

* No 3rd party pod/library was used.
* Inconsistent pattern for view controllers were intended to show capability to write in different code.

### Sample app features:
1. Live API requests from Github.com
2. Persistent storing of loaded data (except images)
   - App will retain previously fetched data so when the app opens with no connection, app will show previously fetched data
3. Fetch pagination
4. Note adding to each user.
   - Works in offline mode, can still add notes to fetched users.
   - Notes added is searchable
6. Caching of Images
7. Connection Reachability detections.
   - If the app detects no connection, API requests are queued up. When the connection is restored, queued requests will automatically be executed.
8. Asynchronous API request
   - API requests does not happen simultaneously.
9. Basic Unit tests for CoreData managers and models
10. Works in Dark mode

![IMG_0878](https://user-images.githubusercontent.com/83448807/116681733-ee8dbe80-a9df-11eb-9d3a-747235b25277.png | width=100)
![IMG_0880](https://user-images.githubusercontent.com/83448807/116681720-ea61a100-a9df-11eb-8189-9c140139ff85.png | width=100)
![IMG_0879](https://user-images.githubusercontent.com/83448807/116681737-f0578200-a9df-11eb-8e0b-e19c93acf82c.png | width=100)


