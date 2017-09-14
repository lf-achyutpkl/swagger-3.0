# Swagger UI for multiple projects
__Integrating multiple API docs in single page__ <p>

## Usage

* Clone microservices branch and navigate to swagger-ui folder in your local machine
* Open index.html file
* Update path to your config file i.e. YOUR_CONFIG_FILE_URL. For example,
  ```JS
    const YOUR_CONFIG_FILE_URL = 'https://raw.githubusercontent.com/lf-achyutpkl/swagger-3.0/microservices/swagger-ui/config.json';
  ```

  > Your config file must match following pattern:
  ```JS
    {
      "default": "default service yaml file path",
      "service": {
        "service1": "service1 yaml file path",
        "service2": "service2 yaml file path"
      }
    }

    //For single project, just add default url.
  ```