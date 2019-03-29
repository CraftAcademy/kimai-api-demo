### Kimai time tracker API

Kimai demo api url: `https://demo.kimai.org/api`

A HTML file to try out the Kimai api. To run it open the `api.html` in your browser. The url you need to hit, username and password are prefilled.

#### Kimai api docs

To get a list of endpoints you can hit, visit `https://demo.kimai.org/api/doc` in your browser.

#### Credentials

Credentials you can use with the demo kimai server.

| USERNAME      | PASSWORD     | ROLE                | DESCRIPTION |
| ------------- | ------------ | ------------------- | ----------- |
| john_user     | api_kitten   | User                |
| chris_user    | api_kitten   | User                | deactivated |
| tony_teamlead | api_kitten   | Teamlead            |
| anna_admin    | api_kitten   | Administrator       |
| susan_super   | api_kitten   | Super-Administrator |
| admin         | api_password | Super-Administrator | no records  |

### Authentication
When calling the API you have to submit two additional header with every call for authentication:

- X-AUTH-USER - holds the username or email
- X-AUTH-TOKEN - holds the users API password, which he can set in his profile


