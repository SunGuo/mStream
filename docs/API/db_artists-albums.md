**Get All Albums for an Artist**
----
  Will retrieve all albums for a given artist name

* **URL**

  /db/artists-albums

* **Method:**

  `POST`

*  **JSON Params**

   **Required:**

   `artist` - directory to get contents from


* **JSON Example**

  ```
  {
    'artist': 'Artist Name'
  }
  ```

* **Success Response:**

  * **Code:** 200 <br />
    **Content:** `['Album1', 'Album2', 'Album3']`
