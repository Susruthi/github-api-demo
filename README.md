# github-api-demo
1.Open Advanced REST Client
2.Url : https://api.github.com/users/ankireddy501
3.Http Method : GET
4.Headers : User-Agent:Mozilla/5.0 (Windows NT 6.1; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/58.0.3029.110 Safari/537.36
Response :'''
```json
{
  "login": "ankireddy501",
  "id": 7135007,
  "avatar_url": "https://avatars0.githubusercontent.com/u/7135007?v=3",
  "gravatar_id": "",
  "url": "https://api.github.com/users/ankireddy501",
  "html_url": "https://github.com/ankireddy501",
  "followers_url": "https://api.github.com/users/ankireddy501/followers",
  "following_url": "https://api.github.com/users/ankireddy501/following{/other_user}",
  "gists_url": "https://api.github.com/users/ankireddy501/gists{/gist_id}",
  "starred_url": "https://api.github.com/users/ankireddy501/starred{/owner}{/repo}",
  "subscriptions_url": "https://api.github.com/users/ankireddy501/subscriptions",
  "organizations_url": "https://api.github.com/users/ankireddy501/orgs",
  "repos_url": "https://api.github.com/users/ankireddy501/repos",
  "events_url": "https://api.github.com/users/ankireddy501/events{/privacy}",
  "received_events_url": "https://api.github.com/users/ankireddy501/received_events",
  "type": "User",
  "site_admin": false,
  "name": "Ankireddy ",
  "company": null,
  "blog": "",
  "location": "chennai",
  "email": null,
  "hireable": null,
  "bio": null,
  "public_repos": 17,
  "public_gists": 0,
  "followers": 5,
  "following": 1,
  "created_at": "2014-04-02T05:36:08Z",
  "updated_at": "2017-06-08T18:11:29Z"
}
```
#### curl -X GET https://api.github.com

```json
curl -X GET https://api.github.com
{
  "current_user_url": "https://api.github.com/user",
  "current_user_authorizations_html_url": "https://github.com/settings/connections/applications{/client_id}",
  "authorizations_url": "https://api.github.com/authorizations",
  "code_search_url": "https://api.github.com/search/code?q={query}{&page,per_page,sort,order}",
  "commit_search_url": "https://api.github.com/search/commits?q={query}{&page,per_page,sort,order}",
  "emails_url": "https://api.github.com/user/emails",
  "emojis_url": "https://api.github.com/emojis",
  "events_url": "https://api.github.com/events",
  "feeds_url": "https://api.github.com/feeds",
  "followers_url": "https://api.github.com/user/followers",
  "following_url": "https://api.github.com/user/following{/target}",
  "gists_url": "https://api.github.com/gists{/gist_id}",
  "hub_url": "https://api.github.com/hub",
  "issue_search_url": "https://api.github.com/search/issues?q={query}{&page,per_page,sort,order}",
  "issues_url": "https://api.github.com/issues",
  "keys_url": "https://api.github.com/user/keys",
  "notifications_url": "https://api.github.com/notifications",
  "organization_repositories_url": "https://api.github.com/orgs/{org}/repos{?type,page,per_page,sort}",
  "organization_url": "https://api.github.com/orgs/{org}",
  "public_gists_url": "https://api.github.com/gists/public",
  "rate_limit_url": "https://api.github.com/rate_limit",
  "repository_url": "https://api.github.com/repos/{owner}/{repo}",
  "repository_search_url": "https://api.github.com/search/repositories?q={query}{&page,per_page,sort,order}",
  "current_user_repositories_url": "https://api.github.com/user/repos{?type,page,per_page,sort}",
  "starred_url": "https://api.github.com/user/starred{/owner}{/repo}",
  "starred_gists_url": "https://api.github.com/gists/starred",
  "team_url": "https://api.github.com/teams",
  "user_url": "https://api.github.com/users/{user}",
  "user_organizations_url": "https://api.github.com/user/orgs",
  "user_repositories_url": "https://api.github.com/users/{user}/repos{?type,page,per_page,sort}",
  "user_search_url": "https://api.github.com/search/users?q={query}{&page,per_page,sort,order}"
}
```
###curl -X GET https://api.github.com/gists/starred
```json
{
  "message": "Requires authentication",
  "documentation_url": "https://developer.github.com/v3/#authentication"
}
```
### curl -X GET -u ankireddy501:******* https://api.github.com/user
```json
{
  "login": "ankireddy501",
  "id": 7135007,
  "avatar_url": "https://avatars0.githubusercontent.com/u/7135007?v=3",
  "gravatar_id": "",
  "url": "https://api.github.com/users/ankireddy501",
  "html_url": "https://github.com/ankireddy501",
  "followers_url": "https://api.github.com/users/ankireddy501/followers",
  "following_url": "https://api.github.com/users/ankireddy501/following{/other_user}",
  "gists_url": "https://api.github.com/users/ankireddy501/gists{/gist_id}",
  "starred_url": "https://api.github.com/users/ankireddy501/starred{/owner}{/repo}",
  "subscriptions_url": "https://api.github.com/users/ankireddy501/subscriptions",
  "organizations_url": "https://api.github.com/users/ankireddy501/orgs",
  "repos_url": "https://api.github.com/users/ankireddy501/repos",
  "events_url": "https://api.github.com/users/ankireddy501/events{/privacy}",
  "received_events_url": "https://api.github.com/users/ankireddy501/received_events",
  "type": "User",
  "site_admin": false,
  "name": "Ankireddy ",
  "company": null,
  "blog": "",
  "location": "chennai",
  "email": "reddy.501@gmail.com",
  "hireable": null,
  "bio": null,
  "public_repos": 19,
  "public_gists": 0,
  "followers": 5,
  "following": 1,
  "created_at": "2014-04-02T05:36:08Z",
  "updated_at": "2017-06-09T12:53:37Z",
  "private_gists": 0,
  "total_private_repos": 5,
  "owned_private_repos": 5,
  "disk_usage": 193535,
  "collaborators": 2,
  "two_factor_authentication": false,
  "plan": {
    "name": "free",
    "space": 976562499,
    "collaborators": 0,
    "private_repos": 0
  }
}
```
https://blogs.infosupport.com/accessing-githubs-rest-api-with-curl/
