# Server

## FAQ

<details>
    <summary>Click To See The FAQ
    </summary>
    
- Can you give any detail on the panel/api/server language ?
  - JavaScript (using Node.JS JavaScript Engine)
  - Using [Express](https://github.com/expressjs/express) as web server and the view engine [EJS](https://github.com/mde/ejs)
  
- What will the server handle ?
    - Panel (will use [API](https://www.redhat.com/en/topics/api/what-are-application-programming-interfaces))
        - Logs Show (with filters)
        - Logs Download
        - Stub Build
        
    - [API](https://www.redhat.com/en/topics/api/what-are-application-programming-interfaces) requests
        - Auth
        - Logs receiving
        - Logs sending (for Panel Logs Download & webhook/telegram sending)
        - Stub build
        - Rate Limit(from the API itself against the abuser)
</details>

## License

OpenStealer is distributed under the [GNU Affero General Public License](https://www.gnu.org/licenses/agpl-3.0.en.html), see [LICENSE](https://github.com/OpenStealer/Server/blob/main/LICENSE.md) and [NOTICE](https://github.com/OpenStealer/Server/blob/main/NOTICE.md) for more information.
