# che-vue-cli

* [Create a project](https://cli.vuejs.org/guide/creating-a-project.html)

   `vue create hello-world`

* Create **vue.config.js**
    ```javascript
    module.exports = {
        devServer: {
            disableHostCheck: true
        },
    }
    ```
* Create Run Command
  * Command line
    ```bash
        cd  ${current.project.path}
        yarn serve
    ```
  * Preview URL
    ```url
        http://${server.port.8080/tcp}
    ```