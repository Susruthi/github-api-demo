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
### curl -X GET https://api.github.com/users/ankireddy501
``` json
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
  "public_repos": 19,
  "public_gists": 0,
  "followers": 5,
  "following": 1,
  "created_at": "2014-04-02T05:36:08Z",
  "updated_at": "2017-06-09T12:53:37Z"
}
```
 ### GET https://api.github.com/user
 ```json
 {
"login": "Susruthi",
"id": 29282131,
"avatar_url": "https://avatars3.githubusercontent.com/u/29282131?v=3",
"gravatar_id": "",
"url": "https://api.github.com/users/Susruthi",
"html_url": "https://github.com/Susruthi",
"followers_url": "https://api.github.com/users/Susruthi/followers",
"following_url": "https://api.github.com/users/Susruthi/following{/other_user}",
"gists_url": "https://api.github.com/users/Susruthi/gists{/gist_id}",
"starred_url": "https://api.github.com/users/Susruthi/starred{/owner}{/repo}",
"subscriptions_url": "https://api.github.com/users/Susruthi/subscriptions",
"organizations_url": "https://api.github.com/users/Susruthi/orgs",
"repos_url": "https://api.github.com/users/Susruthi/repos",
"events_url": "https://api.github.com/users/Susruthi/events{/privacy}",
"received_events_url": "https://api.github.com/users/Susruthi/received_events",
"type": "User",
"site_admin": false,
"name": "Susruthi",
"company": null,
"blog": "",
"location": "Chennai",
"email": "alaparthi.susruthi@gmail.com",
"hireable": null,
"bio": null,
"public_repos": 3,
"public_gists": 0,
"followers": 0,
"following": 0,
"created_at": "2017-06-08T15:00:05Z",
"updated_at": "2017-06-12T11:40:54Z",
"private_gists": 0,
"total_private_repos": 0,
"owned_private_repos": 0,
"disk_usage": 0,
"collaborators": 0,
"two_factor_authentication": false,
"plan": {
        "name": "free",
        "space": 976562499,
        "collaborators": 0,
        "private_repos": 0
    }
}
```
### GET https://api.github.com/authorizations
```json
[
  {
"id": 107464622,
"url": "https://api.github.com/authorizations/107464622",
"app": {
"name": "Gist",
"url": "https://gist.github.com",
"client_id": "7e0a3cd836d3e544dbd9"
},
"token": "",
"hashed_token": "779c871e413b853918e4e2b0f1762c2718057ec18ba9bc39eb4e125cbde6d2f1",
"token_last_eight": "3f69a0bd",
"note": null,
"note_url": null,
"created_at": "2017-06-08T15:03:52Z",
"updated_at": "2017-06-08T15:03:53Z",
"scopes": [],
"fingerprint": null
},
  {
"id": 108055945,
"url": "https://api.github.com/authorizations/108055945",
"app": {
"name": "GitHub Desktop",
"url": "https://desktop.github.com/",
"client_id": "de0e3c7e9973e1c4dd77"
},
"token": "",
"hashed_token": "94c229b5438417fffa5424adb6055f5f7996eccea5738eb64778d6fcba66dc5c",
"token_last_eight": "1d9b16f7",
"note": "GitHub Desktop on SUSR@PCSUSR01",
"note_url": "https://desktop.github.com/",
"created_at": "2017-06-12T06:51:00Z",
"updated_at": "2017-06-12T06:51:00Z",
"scopes": [
  "repo",
  "user"
],
"fingerprint": "77c03d34-4400-47c8-84d4-f174790ca3be"
}
],
```
### GET https://api.github.com/user/emails
```json
[
  {
"email": "alaparthi.susruthi@gmail.com",
"primary": true,
"verified": true,
"visibility": "public"
}
],
```
### GET https://api.github.com/emojis
```json
100: "https://assets-cdn.github.com/images/icons/emoji/unicode/1f4af.png?v7",
1234: "https://assets-cdn.github.com/images/icons/emoji/unicode/1f522.png?v7",
+1: "https://assets-cdn.github.com/images/icons/emoji/unicode/1f44d.png?v7",
-1: "https://assets-cdn.github.com/images/icons/emoji/unicode/1f44e.png?v7",
"1st_place_medal": "https://assets-cdn.github.com/images/icons/emoji/unicode/1f947.png?v7",
"2nd_place_medal": "https://assets-cdn.github.com/images/icons/emoji/unicode/1f948.png?v7",
"3rd_place_medal": "https://assets-cdn.github.com/images/icons/emoji/unicode/1f949.png?v7",
"8ball": "https://assets-cdn.github.com/images/icons/emoji/unicode/1f3b1.png?v7",
"a": "https://assets-cdn.github.com/images/icons/emoji/unicode/1f170.png?v7",
"ab": "https://assets-cdn.github.com/images/icons/emoji/unicode/1f18e.png?v7",
"abc": "https://assets-cdn.github.com/images/icons/emoji/unicode/1f524.png?v7",
"abcd": "https://assets-cdn.github.com/images/icons/emoji/unicode/1f521.png?v7",
"accept": "https://assets-cdn.github.com/images/icons/emoji/unicode/1f251.png?v7",
"aerial_tramway": "https://assets-cdn.github.com/images/icons/emoji/unicode/1f6a1.png?v7",
"afghanistan": "https://assets-cdn.github.com/images/icons/emoji/unicode/1f1e6-1f1eb.png?v7",
"airplane": "https://assets-cdn.github.com/images/icons/emoji/unicode/2708.png?v7",
"aland_islands": "https://assets-cdn.github.com/images/icons/emoji/unicode/1f1e6-1f1fd.png?v7",
"alarm_clock": "https://assets-cdn.github.com/images/icons/emoji/unicode/23f0.png?v7",
"albania": "https://assets-cdn.github.com/images/icons/emoji/unicode/1f1e6-1f1f1.png?v7",
"alembic": "https://assets-cdn.github.com/images/icons/emoji/unicode/2697.png?v7",
"algeria": "https://assets-cdn.github.com/images/icons/emoji/unicode/1f1e9-1f1ff.png?v7",
"alien": "https://assets-cdn.github.com/images/icons/emoji/unicode/1f47d.png?v7",
"ambulance": "https://assets-cdn.github.com/images/icons/emoji/unicode/1f691.png?v7",
"american_samoa": "https://assets-cdn.github.com/images/icons/emoji/unicode/1f1e6-1f1f8.png?v7",
"amphora": "https://assets-cdn.github.com/images/icons/emoji/unicode/1f3fa.png?v7",
"anchor": "https://assets-cdn.github.com/images/icons/emoji/unicode/2693.png?v7",
"andorra": "https://assets-cdn.github.com/images/icons/emoji/unicode/1f1e6-1f1e9.png?v7",
"angel": "https://assets-cdn.github.com/images/icons/emoji/unicode/1f47c.png?v7",
"anger": "https://assets-cdn.github.com/images/icons/emoji/unicode/1f4a2.png?v7",
"angola": "https://assets-cdn.github.com/images/icons/emoji/unicode/1f1e6-1f1f4.png?v7",
"angry": "https://assets-cdn.github.com/images/icons/emoji/unicode/1f620.png?v7",
"anguilla": "https://assets-cdn.github.com/images/icons/emoji/unicode/1f1e6-1f1ee.png?v7",
"anguished": "https://assets-cdn.github.com/images/icons/emoji/unicode/1f627.png?v7",
"ant": "https://assets-cdn.github.com/images/icons/emoji/unicode/1f41c.png?v7",
```
### GET https://api.github.com/events 
```json
  {
"id": "6054841231",
"type": "PushEvent",
"actor": {
"id": 20294050,
"login": "vishwackh",
"display_login": "vishwackh",
"gravatar_id": "",
"url": "https://api.github.com/users/vishwackh",
"avatar_url": "https://avatars.githubusercontent.com/u/20294050?"
},
"repo": {
"id": 94207007,
"name": "vishwackh/vishwackh.github.io",
"url": "https://api.github.com/repos/vishwackh/vishwackh.github.io"
},
"payload": {
"push_id": 1797031008,
"size": 1,
"distinct_size": 1,
"ref": "refs/heads/master",
"head": "2c68b900892a9fdf9cb53f10b0e9bfc9e466269c",
"before": "1926d4d66459d30c2f077859c665a0685f00c1e8",
"commits": [
  {
"sha": "2c68b900892a9fdf9cb53f10b0e9bfc9e466269c",
"author": {
"email": "vishwackh89@gmail.com",
"name": "Vishwanatha V"
},
"message": "Resume Added",
"distinct": true,
"url": "https://api.github.com/repos/vishwackh/vishwackh.github.io/commits/2c68b900892a9fdf9cb53f10b0e9bfc9e466269c"
}
],
},
"public": true,
"created_at": "2017-06-13T12:08:21Z"
},
  {
"id": "6054841221",
"type": "PushEvent",
"actor": {
"id": 29389245,
"login": "peek2much3",
"display_login": "peek2much3",
"gravatar_id": "",
"url": "https://api.github.com/users/peek2much3",
"avatar_url": "https://avatars.githubusercontent.com/u/29389245?"
},
"repo": {
"id": 94151851,
"name": "peek2much3/bash-scripts-collection",
"url": "https://api.github.com/repos/peek2much3/bash-scripts-collection"
},
"payload": {
"push_id": 1797031005,
"size": 1,
"distinct_size": 1,
"ref": "refs/heads/master",
"head": "8b03a12a15feace1df667c540751fcd0f4aa4a56",
"before": "ee42de54591ee49085aa646c552fa595bc160ef6",
"commits": [
  {
"sha": "8b03a12a15feace1df667c540751fcd0f4aa4a56",
"author": {
"email": "peek2much2@yahoo.com",
"name": "peek2much3"
},
"message": "Create README.md",
"distinct": true,
"url": "https://api.github.com/repos/peek2much3/bash-scripts-collection/commits/8b03a12a15feace1df667c540751fcd0f4aa4a56"
}
],
},
"public": true,
"created_at": "2017-06-13T12:08:21Z"
},
  {
"id": "6054841214",
"type": "PullRequestReviewCommentEvent",
"actor": {
"id": 1035015,
"login": "mp911de",
"display_login": "mp911de",
"gravatar_id": "",
"url": "https://api.github.com/users/mp911de",
"avatar_url": "https://avatars.githubusercontent.com/u/1035015?"
},
"repo": {
"id": 1072614,
"name": "spring-projects/spring-data-commons",
"url": "https://api.github.com/repos/spring-projects/spring-data-commons"
},
"payload": {
"action": "created",
"comment": {
"url": "https://api.github.com/repos/spring-projects/spring-data-commons/pulls/comments/121657187",
"pull_request_review_id": 43701510,
"id": 121657187,
"diff_hunk": "@@ -22,94 +22,99 @@ /** * Configuration information for a single repository instance. - * + * * @author Oliver Gierke + * @author Mark Paluch */ public interface RepositoryConfiguration<T extends RepositoryConfigurationSource> { /** * Returns the base packages that the repository was scanned under. -	* +	* * @return */ Iterable<String> getBasePackages(); /** * Returns the interface name of the repository. -	* +	* * @return */ String getRepositoryInterface(); /** * Returns the key to resolve a {@link QueryLookupStrategy} from eventually. -	* ",
"path": "src/main/java/org/springframework/data/repository/config/RepositoryConfiguration.java",
"position": 29,
"original_position": 29,
"commit_id": "79baa7fe1fdf36759ac7f0f9c67ca730c5d06d4c",
"original_commit_id": "612a62b5b54d655cc42a6817a3ffab12985ca82a",
"user": {
"login": "mp911de",
"id": 1035015,
"avatar_url": "https://avatars0.githubusercontent.com/u/1035015?v=3",
"gravatar_id": "",
"url": "https://api.github.com/users/mp911de",
"html_url": "https://github.com/mp911de",
"followers_url": "https://api.github.com/users/mp911de/followers",
"following_url": "https://api.github.com/users/mp911de/following{/other_user}",
"gists_url": "https://api.github.com/users/mp911de/gists{/gist_id}",
"starred_url": "https://api.github.com/users/mp911de/starred{/owner}{/repo}",
"subscriptions_url": "https://api.github.com/users/mp911de/subscriptions",
"organizations_url": "https://api.github.com/users/mp911de/orgs",
"repos_url": "https://api.github.com/users/mp911de/repos",
"events_url": "https://api.github.com/users/mp911de/events{/privacy}",
"received_events_url": "https://api.github.com/users/mp911de/received_events",
"type": "User",
"site_admin": false
},
"body": "Done.",
"created_at": "2017-06-13T12:08:20Z",
"updated_at": "2017-06-13T12:08:20Z",
"html_url": "https://github.com/spring-projects/spring-data-commons/pull/222#discussion_r121657187",
"pull_request_url": "https://api.github.com/repos/spring-projects/spring-data-commons/pulls/222",
"_links": {
"self": {
"href": "https://api.github.com/repos/spring-projects/spring-data-commons/pulls/comments/121657187"
},
"html": {
"href": "https://github.com/spring-projects/spring-data-commons/pull/222#discussion_r121657187"
},
"pull_request": {
"href": "https://api.github.com/repos/spring-projects/spring-data-commons/pulls/222"
}
}
},
"pull_request": {
"url": "https://api.github.com/repos/spring-projects/spring-data-commons/pulls/222",
"id": 123217053,
"html_url": "https://github.com/spring-projects/spring-data-commons/pull/222",
"diff_url": "https://github.com/spring-projects/spring-data-commons/pull/222.diff",
"patch_url": "https://github.com/spring-projects/spring-data-commons/pull/222.patch",
"issue_url": "https://api.github.com/repos/spring-projects/spring-data-commons/issues/222",
"number": 222,
"state": "open",
"locked": false,
"title": "DATACMNS-102 - Allow Repositories to be composed of an arbitrary number of implementation classes",
"user": {
"login": "mp911de",
"id": 1035015,
"avatar_url": "https://avatars0.githubusercontent.com/u/1035015?v=3",
"gravatar_id": "",
"url": "https://api.github.com/users/mp911de",
"html_url": "https://github.com/mp911de",
"followers_url": "https://api.github.com/users/mp911de/followers",
"following_url": "https://api.github.com/users/mp911de/following{/other_user}",
"gists_url": "https://api.github.com/users/mp911de/gists{/gist_id}",
"starred_url": "https://api.github.com/users/mp911de/starred{/owner}{/repo}",
"subscriptions_url": "https://api.github.com/users/mp911de/subscriptions",
"organizations_url": "https://api.github.com/users/mp911de/orgs",
"repos_url": "https://api.github.com/users/mp911de/repos",
"events_url": "https://api.github.com/users/mp911de/events{/privacy}",
"received_events_url": "https://api.github.com/users/mp911de/received_events",
"type": "User",
"site_admin": false
},
"body": "**Do not merge yet.** --- We now use `RepositoryComposition` as backing implementation for repository method calls to implementations. `RepositoryComposition` are subject to `MethodLookup` and argument converter customization to select the target method that should be invoked. A composition consists of one or more fragments that contribute their API backed by an implementation. During configuration, we scan for repository fragments. Fragment implementation candidates derive from the repository interface declaration, specifically the declared interfaces and their order. We scan the class path during fragment scan for each interface and add discovered fragments to the repository composition. The name of the implementation is derived from the simple name of the interface and the implementation suffix. Qualified fragments are top-level interface declarations that are not annotated with `@NoRepositoryBean`. Inherited interfaces are not considered as fragment candidates. ```java interface ComposedRepository extends Repository<Person, Long>, WriteRepository<Person>, ReadRepository<Person>, QueryByExampleExecutor<Person> {} // fragment candidate interface WriteRepository<T> extends BaseRepository {} // fragment implementation class WriteRepositoryImpl<T> extends BaseRepositoryImpl implements WriteRepository<T> {} // transient dependency of ComposedRepository, not a fragment candidate interface BaseRepository {} // ignored class BaseRepositoryImpl implements BaseRepository {} // fragment candidate interface ReadRepository<T> extends BaseRepository {} // fragment implementation class ReadRepositoryImpl<T> implements ReadRepository<T> {} // excluded fragment (can be added by RepositoryFactorySupport) @NoRepositoryBean interface QueryByExampleExecutor<Person> {} ``` We create a `RepositoryComposition` from the discovered fragments in the order of interface declaration in the repository interface and supply the composition to the actual repository creation. --- Related ticket: [DATACMNS-102](https://jira.spring.io/browse/DATACMNS-102).",
"created_at": "2017-05-31T08:16:57Z",
"updated_at": "2017-06-13T12:08:20Z",
"closed_at": null,
"merged_at": null,
"merge_commit_sha": "de9e628f5c142016c7f5bf1b39bbeb112739634a",
"assignee": null,
"assignees": [],
"requested_reviewers": [],
"milestone": null,
"commits_url": "https://api.github.com/repos/spring-projects/spring-data-commons/pulls/222/commits",
"review_comments_url": "https://api.github.com/repos/spring-projects/spring-data-commons/pulls/222/comments",
"review_comment_url": "https://api.github.com/repos/spring-projects/spring-data-commons/pulls/comments{/number}",
"comments_url": "https://api.github.com/repos/spring-projects/spring-data-commons/issues/222/comments",
"statuses_url": "https://api.github.com/repos/spring-projects/spring-data-commons/statuses/79baa7fe1fdf36759ac7f0f9c67ca730c5d06d4c",
"head": {
"label": "spring-projects:issue/DATACMNS-102",
"ref": "issue/DATACMNS-102",
"sha": "79baa7fe1fdf36759ac7f0f9c67ca730c5d06d4c",
"user": {
"login": "spring-projects",
"id": 317776,
"avatar_url": "https://avatars3.githubusercontent.com/u/317776?v=3",
"gravatar_id": "",
"url": "https://api.github.com/users/spring-projects",
"html_url": "https://github.com/spring-projects",
"followers_url": "https://api.github.com/users/spring-projects/followers",
"following_url": "https://api.github.com/users/spring-projects/following{/other_user}",
"gists_url": "https://api.github.com/users/spring-projects/gists{/gist_id}",
"starred_url": "https://api.github.com/users/spring-projects/starred{/owner}{/repo}",
"subscriptions_url": "https://api.github.com/users/spring-projects/subscriptions",
"organizations_url": "https://api.github.com/users/spring-projects/orgs",
"repos_url": "https://api.github.com/users/spring-projects/repos",
"events_url": "https://api.github.com/users/spring-projects/events{/privacy}",
"received_events_url": "https://api.github.com/users/spring-projects/received_events",
"type": "Organization",
"site_admin": false
},
"repo": {
"id": 1072614,
"name": "spring-data-commons",
"full_name": "spring-projects/spring-data-commons",
"owner": {
"login": "spring-projects",
"id": 317776,
"avatar_url": "https://avatars3.githubusercontent.com/u/317776?v=3",
"gravatar_id": "",
"url": "https://api.github.com/users/spring-projects",
"html_url": "https://github.com/spring-projects",
"followers_url": "https://api.github.com/users/spring-projects/followers",
"following_url": "https://api.github.com/users/spring-projects/following{/other_user}",
"gists_url": "https://api.github.com/users/spring-projects/gists{/gist_id}",
"starred_url": "https://api.github.com/users/spring-projects/starred{/owner}{/repo}",
"subscriptions_url": "https://api.github.com/users/spring-projects/subscriptions",
"organizations_url": "https://api.github.com/users/spring-projects/orgs",
"repos_url": "https://api.github.com/users/spring-projects/repos",
"events_url": "https://api.github.com/users/spring-projects/events{/privacy}",
"received_events_url": "https://api.github.com/users/spring-projects/received_events",
"type": "Organization",
"site_admin": false
},
"private": false,
"html_url": "https://github.com/spring-projects/spring-data-commons",
"description": "Spring Data Commons. Interfaces and code shared between the various datastore specific implementations.",
"fork": false,
"url": "https://api.github.com/repos/spring-projects/spring-data-commons",
"forks_url": "https://api.github.com/repos/spring-projects/spring-data-commons/forks",
"keys_url": "https://api.github.com/repos/spring-projects/spring-data-commons/keys{/key_id}",
"collaborators_url": "https://api.github.com/repos/spring-projects/spring-data-commons/collaborators{/collaborator}",
"teams_url": "https://api.github.com/repos/spring-projects/spring-data-commons/teams",
"hooks_url": "https://api.github.com/repos/spring-projects/spring-data-commons/hooks",
"issue_events_url": "https://api.github.com/repos/spring-projects/spring-data-commons/issues/events{/number}",
"events_url": "https://api.github.com/repos/spring-projects/spring-data-commons/events",
"assignees_url": "https://api.github.com/repos/spring-projects/spring-data-commons/assignees{/user}",
"branches_url": "https://api.github.com/repos/spring-projects/spring-data-commons/branches{/branch}",
"tags_url": "https://api.github.com/repos/spring-projects/spring-data-commons/tags",
"blobs_url": "https://api.github.com/repos/spring-projects/spring-data-commons/git/blobs{/sha}",
"git_tags_url": "https://api.github.com/repos/spring-projects/spring-data-commons/git/tags{/sha}",
"git_refs_url": "https://api.github.com/repos/spring-projects/spring-data-commons/git/refs{/sha}",
"trees_url": "https://api.github.com/repos/spring-projects/spring-data-commons/git/trees{/sha}",
"statuses_url": "https://api.github.com/repos/spring-projects/spring-data-commons/statuses/{sha}",
"languages_url": "https://api.github.com/repos/spring-projects/spring-data-commons/languages",
"stargazers_url": "https://api.github.com/repos/spring-projects/spring-data-commons/stargazers",
"contributors_url": "https://api.github.com/repos/spring-projects/spring-data-commons/contributors",
"subscribers_url": "https://api.github.com/repos/spring-projects/spring-data-commons/subscribers",
"subscription_url": "https://api.github.com/repos/spring-projects/spring-data-commons/subscription",
"commits_url": "https://api.github.com/repos/spring-projects/spring-data-commons/commits{/sha}",
"git_commits_url": "https://api.github.com/repos/spring-projects/spring-data-commons/git/commits{/sha}",
"comments_url": "https://api.github.com/repos/spring-projects/spring-data-commons/comments{/number}",
"issue_comment_url": "https://api.github.com/repos/spring-projects/spring-data-commons/issues/comments{/number}",
"contents_url": "https://api.github.com/repos/spring-projects/spring-data-commons/contents/{+path}",
"compare_url": "https://api.github.com/repos/spring-projects/spring-data-commons/compare/{base}...{head}",
"merges_url": "https://api.github.com/repos/spring-projects/spring-data-commons/merges",
"archive_url": "https://api.github.com/repos/spring-projects/spring-data-commons/{archive_format}{/ref}",
"downloads_url": "https://api.github.com/repos/spring-projects/spring-data-commons/downloads",
"issues_url": "https://api.github.com/repos/spring-projects/spring-data-commons/issues{/number}",
"pulls_url": "https://api.github.com/repos/spring-projects/spring-data-commons/pulls{/number}",
"milestones_url": "https://api.github.com/repos/spring-projects/spring-data-commons/milestones{/number}",
"notifications_url": "https://api.github.com/repos/spring-projects/spring-data-commons/notifications{?since,all,participating}",
"labels_url": "https://api.github.com/repos/spring-projects/spring-data-commons/labels{/name}",
"releases_url": "https://api.github.com/repos/spring-projects/spring-data-commons/releases{/id}",
"deployments_url": "https://api.github.com/repos/spring-projects/spring-data-commons/deployments",
"created_at": "2010-11-11T20:19:31Z",
"updated_at": "2017-06-13T02:21:19Z",
"pushed_at": "2017-06-13T12:07:41Z",
"git_url": "git://github.com/spring-projects/spring-data-commons.git",
"ssh_url": "git@github.com:spring-projects/spring-data-commons.git",
"clone_url": "https://github.com/spring-projects/spring-data-commons.git",
"svn_url": "https://github.com/spring-projects/spring-data-commons",
"homepage": "http://projects.spring.io/spring-data",
"size": 6885,
"stargazers_count": 269,
"watchers_count": 269,
"language": "Java",
"has_issues": false,
"has_projects": true,
"has_downloads": true,
"has_wiki": true,
"has_pages": false,
"forks_count": 270,
"mirror_url": null,
"open_issues_count": 12,
"forks": 270,
"open_issues": 12,
"watchers": 269,
"default_branch": "master"
}
},
"base": {
"label": "spring-projects:master",
"ref": "master",
"sha": "13907152fb2781c1ef92563af526e20e272da5e9",
"user": {
"login": "spring-projects",
"id": 317776,
"avatar_url": "https://avatars3.githubusercontent.com/u/317776?v=3",
"gravatar_id": "",
"url": "https://api.github.com/users/spring-projects",
"html_url": "https://github.com/spring-projects",
"followers_url": "https://api.github.com/users/spring-projects/followers",
"following_url": "https://api.github.com/users/spring-projects/following{/other_user}",
"gists_url": "https://api.github.com/users/spring-projects/gists{/gist_id}",
"starred_url": "https://api.github.com/users/spring-projects/starred{/owner}{/repo}",
"subscriptions_url": "https://api.github.com/users/spring-projects/subscriptions",
"organizations_url": "https://api.github.com/users/spring-projects/orgs",
"repos_url": "https://api.github.com/users/spring-projects/repos",
"events_url": "https://api.github.com/users/spring-projects/events{/privacy}",
"received_events_url": "https://api.github.com/users/spring-projects/received_events",
"type": "Organization",
"site_admin": false
},
"repo": {
"id": 1072614,
"name": "spring-data-commons",
"full_name": "spring-projects/spring-data-commons",
"owner": {
"login": "spring-projects",
"id": 317776,
"avatar_url": "https://avatars3.githubusercontent.com/u/317776?v=3",
"gravatar_id": "",
"url": "https://api.github.com/users/spring-projects",
"html_url": "https://github.com/spring-projects",
"followers_url": "https://api.github.com/users/spring-projects/followers",
"following_url": "https://api.github.com/users/spring-projects/following{/other_user}",
"gists_url": "https://api.github.com/users/spring-projects/gists{/gist_id}",
"starred_url": "https://api.github.com/users/spring-projects/starred{/owner}{/repo}",
"subscriptions_url": "https://api.github.com/users/spring-projects/subscriptions",
"organizations_url": "https://api.github.com/users/spring-projects/orgs",
"repos_url": "https://api.github.com/users/spring-projects/repos",
"events_url": "https://api.github.com/users/spring-projects/events{/privacy}",
"received_events_url": "https://api.github.com/users/spring-projects/received_events",
"type": "Organization",
"site_admin": false
},
"private": false,
"html_url": "https://github.com/spring-projects/spring-data-commons",
"description": "Spring Data Commons. Interfaces and code shared between the various datastore specific implementations.",
"fork": false,
"url": "https://api.github.com/repos/spring-projects/spring-data-commons",
"forks_url": "https://api.github.com/repos/spring-projects/spring-data-commons/forks",
"keys_url": "https://api.github.com/repos/spring-projects/spring-data-commons/keys{/key_id}",
"collaborators_url": "https://api.github.com/repos/spring-projects/spring-data-commons/collaborators{/collaborator}",
"teams_url": "https://api.github.com/repos/spring-projects/spring-data-commons/teams",
"hooks_url": "https://api.github.com/repos/spring-projects/spring-data-commons/hooks",
"issue_events_url": "https://api.github.com/repos/spring-projects/spring-data-commons/issues/events{/number}",
"events_url": "https://api.github.com/repos/spring-projects/spring-data-commons/events",
"assignees_url": "https://api.github.com/repos/spring-projects/spring-data-commons/assignees{/user}",
"branches_url": "https://api.github.com/repos/spring-projects/spring-data-commons/branches{/branch}",
"tags_url": "https://api.github.com/repos/spring-projects/spring-data-commons/tags",
"blobs_url": "https://api.github.com/repos/spring-projects/spring-data-commons/git/blobs{/sha}",
"git_tags_url": "https://api.github.com/repos/spring-projects/spring-data-commons/git/tags{/sha}",
"git_refs_url": "https://api.github.com/repos/spring-projects/spring-data-commons/git/refs{/sha}",
"trees_url": "https://api.github.com/repos/spring-projects/spring-data-commons/git/trees{/sha}",
"statuses_url": "https://api.github.com/repos/spring-projects/spring-data-commons/statuses/{sha}",
"languages_url": "https://api.github.com/repos/spring-projects/spring-data-commons/languages",
"stargazers_url": "https://api.github.com/repos/spring-projects/spring-data-commons/stargazers",
"contributors_url": "https://api.github.com/repos/spring-projects/spring-data-commons/contributors",
"subscribers_url": "https://api.github.com/repos/spring-projects/spring-data-commons/subscribers",
"subscription_url": "https://api.github.com/repos/spring-projects/spring-data-commons/subscription",
"commits_url": "https://api.github.com/repos/spring-projects/spring-data-commons/commits{/sha}",
"git_commits_url": "https://api.github.com/repos/spring-projects/spring-data-commons/git/commits{/sha}",
"comments_url": "https://api.github.com/repos/spring-projects/spring-data-commons/comments{/number}",
"issue_comment_url": "https://api.github.com/repos/spring-projects/spring-data-commons/issues/comments{/number}",
"contents_url": "https://api.github.com/repos/spring-projects/spring-data-commons/contents/{+path}",
"compare_url": "https://api.github.com/repos/spring-projects/spring-data-commons/compare/{base}...{head}",
"merges_url": "https://api.github.com/repos/spring-projects/spring-data-commons/merges",
"archive_url": "https://api.github.com/repos/spring-projects/spring-data-commons/{archive_format}{/ref}",
"downloads_url": "https://api.github.com/repos/spring-projects/spring-data-commons/downloads",
"issues_url": "https://api.github.com/repos/spring-projects/spring-data-commons/issues{/number}",
"pulls_url": "https://api.github.com/repos/spring-projects/spring-data-commons/pulls{/number}",
"milestones_url": "https://api.github.com/repos/spring-projects/spring-data-commons/milestones{/number}",
"notifications_url": "https://api.github.com/repos/spring-projects/spring-data-commons/notifications{?since,all,participating}",
"labels_url": "https://api.github.com/repos/spring-projects/spring-data-commons/labels{/name}",
"releases_url": "https://api.github.com/repos/spring-projects/spring-data-commons/releases{/id}",
"deployments_url": "https://api.github.com/repos/spring-projects/spring-data-commons/deployments",
"created_at": "2010-11-11T20:19:31Z",
"updated_at": "2017-06-13T02:21:19Z",
"pushed_at": "2017-06-13T12:07:41Z",
"git_url": "git://github.com/spring-projects/spring-data-commons.git",
"ssh_url": "git@github.com:spring-projects/spring-data-commons.git",
"clone_url": "https://github.com/spring-projects/spring-data-commons.git",
"svn_url": "https://github.com/spring-projects/spring-data-commons",
"homepage": "http://projects.spring.io/spring-data",
"size": 6885,
"stargazers_count": 269,
"watchers_count": 269,
"language": "Java",
"has_issues": false,
"has_projects": true,
"has_downloads": true,
"has_wiki": true,
"has_pages": false,
"forks_count": 270,
"mirror_url": null,
"open_issues_count": 12,
"forks": 270,
"open_issues": 12,
"watchers": 269,
"default_branch": "master"
}
},
"_links": {
"self": {
"href": "https://api.github.com/repos/spring-projects/spring-data-commons/pulls/222"
},
"html": {
"href": "https://github.com/spring-projects/spring-data-commons/pull/222"
},
"issue": {
"href": "https://api.github.com/repos/spring-projects/spring-data-commons/issues/222"
},
"comments": {
"href": "https://api.github.com/repos/spring-projects/spring-data-commons/issues/222/comments"
},
"review_comments": {
"href": "https://api.github.com/repos/spring-projects/spring-data-commons/pulls/222/comments"
},
"review_comment": {
"href": "https://api.github.com/repos/spring-projects/spring-data-commons/pulls/comments{/number}"
},
"commits": {
"href": "https://api.github.com/repos/spring-projects/spring-data-commons/pulls/222/commits"
},
"statuses": {
"href": "https://api.github.com/repos/spring-projects/spring-data-commons/statuses/79baa7fe1fdf36759ac7f0f9c67ca730c5d06d4c"
}
}
}
},
"public": true,
"created_at": "2017-06-13T12:08:20Z",
"org": {
"id": 317776,
"login": "spring-projects",
"gravatar_id": "",
"url": "https://api.github.com/orgs/spring-projects",
"avatar_url": "https://avatars.githubusercontent.com/u/317776?"
}
},
```
### GET https://api.github.com/feeds
```json {
"timeline_url": "https://github.com/timeline",
"user_url": "https://github.com/{user}",
"current_user_public_url": "https://github.com/Susruthi",
"current_user_url": "https://github.com/Susruthi.private.atom?token=Ab7PU_D8qv6ofcD4YAMfLgPMWl3UIaemks63S7cxwA==",
"current_user_actor_url": "https://github.com/Susruthi.private.actor.atom?token=Ab7PU-3rTkplgFgOImO9yfiDtvv7V4Ccks63S7cxwA==",
"current_user_organization_url": "",
"current_user_organization_urls": [],
"_links": {
"timeline": {
"href": "https://github.com/timeline",
"type": "application/atom+xml"
},
"user": {
"href": "https://github.com/{user}",
"type": "application/atom+xml"
},
"current_user_public": {
"href": "https://github.com/Susruthi",
"type": "application/atom+xml"
},
"current_user": {
"href": "https://github.com/Susruthi.private.atom?token=Ab7PU_D8qv6ofcD4YAMfLgPMWl3UIaemks63S7cxwA==",
"type": "application/atom+xml"
},
"current_user_actor": {
"href": "https://github.com/Susruthi.private.actor.atom?token=Ab7PU-3rTkplgFgOImO9yfiDtvv7V4Ccks63S7cxwA==",
"type": "application/atom+xml"
},
"current_user_organization": {
"href": "",
"type": ""
},
"current_user_organizations": [],
}
}
```
### GET https://api.github.com/notifications

### GET https://api.github.com/orgs/tcs  (https://api.github.com/orgs{/orgId})
```json 
{
"login": "tcs",
"id": 640825,
"url": "https://api.github.com/orgs/tcs",
"repos_url": "https://api.github.com/orgs/tcs/repos",
"events_url": "https://api.github.com/orgs/tcs/events",
"hooks_url": "https://api.github.com/orgs/tcs/hooks",
"issues_url": "https://api.github.com/orgs/tcs/issues",
"members_url": "https://api.github.com/orgs/tcs/members{/member}",
"public_members_url": "https://api.github.com/orgs/tcs/public_members{/member}",
"avatar_url": "https://avatars3.githubusercontent.com/u/640825?v=3",
"description": null,
"name": "TCS",
"company": null,
"blog": null,
"location": null,
"email": null,
"has_organization_projects": true,
"has_repository_projects": true,
"public_repos": 1,
"public_gists": 0,
"followers": 0,
"following": 0,
"html_url": "https://github.com/tcs",
"created_at": "2011-02-27T13:44:30Z",
"updated_at": "2015-10-15T09:26:09Z",
"type": "Organization"
}
```
### GET https://api.github.com/gists/public
```json
  {
"url": "https://api.github.com/gists/b809dbc6a55d1f8ee8029b9e45eed249",
"forks_url": "https://api.github.com/gists/b809dbc6a55d1f8ee8029b9e45eed249/forks",
"commits_url": "https://api.github.com/gists/b809dbc6a55d1f8ee8029b9e45eed249/commits",
"id": "b809dbc6a55d1f8ee8029b9e45eed249",
"git_pull_url": "https://gist.github.com/b809dbc6a55d1f8ee8029b9e45eed249.git",
"git_push_url": "https://gist.github.com/b809dbc6a55d1f8ee8029b9e45eed249.git",
"html_url": "https://gist.github.com/b809dbc6a55d1f8ee8029b9e45eed249",
"files": {
"Как из резинок сделать рыбий хвост инструкция.md": {
"filename": "Как из резинок сделать рыбий хвост инструкция.md",
"type": "text/plain",
"language": "Markdown",
"raw_url": "https://gist.githubusercontent.com/anonymous/b809dbc6a55d1f8ee8029b9e45eed249/raw/b48f93bc6f25d564266401b7bc4f06c5a29d64ff/%D0%9A%D0%B0%D0%BA%20%D0%B8%D0%B7%20%D1%80%D0%B5%D0%B7%D0%B8%D0%BD%D0%BE%D0%BA%20%D1%81%D0%B4%D0%B5%D0%BB%D0%B0%D1%82%D1%8C%20%D1%80%D1%8B%D0%B1%D0%B8%D0%B9%20%D1%85%D0%B2%D0%BE%D1%81%D1%82%20%D0%B8%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%86%D0%B8%D1%8F.md",
"size": 6778
}
},
"public": true,
"created_at": "2017-06-13T12:16:16Z",
"updated_at": "2017-06-13T12:16:17Z",
"description": "Как из резинок сделать рыбий хвост инструкция",
"comments": 0,
"user": null,
"comments_url": "https://api.github.com/gists/b809dbc6a55d1f8ee8029b9e45eed249/comments",
"truncated": false
},
  {
"url": "https://api.github.com/gists/a086ba28acac91444ff007f77fdb5520",
"forks_url": "https://api.github.com/gists/a086ba28acac91444ff007f77fdb5520/forks",
"commits_url": "https://api.github.com/gists/a086ba28acac91444ff007f77fdb5520/commits",
"id": "a086ba28acac91444ff007f77fdb5520",
"git_pull_url": "https://gist.github.com/a086ba28acac91444ff007f77fdb5520.git",
"git_push_url": "https://gist.github.com/a086ba28acac91444ff007f77fdb5520.git",
"html_url": "https://gist.github.com/a086ba28acac91444ff007f77fdb5520",
"files": {
"Скачать диспетчер приложения на андроид.md": {
"filename": "Скачать диспетчер приложения на андроид.md",
"type": "text/plain",
"language": "Markdown",
"raw_url": "https://gist.githubusercontent.com/anonymous/a086ba28acac91444ff007f77fdb5520/raw/8ca063a30996be8d023196fd2d8431bd5673c9ba/%D0%A1%D0%BA%D0%B0%D1%87%D0%B0%D1%82%D1%8C%20%D0%B4%D0%B8%D1%81%D0%BF%D0%B5%D1%82%D1%87%D0%B5%D1%80%20%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BD%D0%B0%20%D0%B0%D0%BD%D0%B4%D1%80%D0%BE%D0%B8%D0%B4.md",
"size": 7243
}
},
"public": true,
"created_at": "2017-06-13T12:16:15Z",
"updated_at": "2017-06-13T12:16:15Z",
"description": "Скачать диспетчер приложения на андроид",
"comments": 0,
"user": null,
"comments_url": "https://api.github.com/gists/a086ba28acac91444ff007f77fdb5520/comments",
"truncated": false
},
  {
"url": "https://api.github.com/gists/96c9805268c8155af7ed33b2cc267715",
"forks_url": "https://api.github.com/gists/96c9805268c8155af7ed33b2cc267715/forks",
"commits_url": "https://api.github.com/gists/96c9805268c8155af7ed33b2cc267715/commits",
"id": "96c9805268c8155af7ed33b2cc267715",
"git_pull_url": "https://gist.github.com/96c9805268c8155af7ed33b2cc267715.git",
"git_push_url": "https://gist.github.com/96c9805268c8155af7ed33b2cc267715.git",
"html_url": "https://gist.github.com/96c9805268c8155af7ed33b2cc267715",
"files": {
"Игра на андроид touchgrind bmx полная версия.md": {
"filename": "Игра на андроид touchgrind bmx полная версия.md",
"type": "text/plain",
"language": "Markdown",
"raw_url": "https://gist.githubusercontent.com/anonymous/96c9805268c8155af7ed33b2cc267715/raw/848238458cd2ab3573a45508ba6909fb4a61d787/%D0%98%D0%B3%D1%80%D0%B0%20%D0%BD%D0%B0%20%D0%B0%D0%BD%D0%B4%D1%80%D0%BE%D0%B8%D0%B4%20touchgrind%20bmx%20%D0%BF%D0%BE%D0%BB%D0%BD%D0%B0%D1%8F%20%D0%B2%D0%B5%D1%80%D1%81%D0%B8%D1%8F.md",
"size": 4707
}
},
"public": true,
"created_at": "2017-06-13T12:16:15Z",
"updated_at": "2017-06-13T12:16:15Z",
"description": "Игра на андроид touchgrind bmx полная версия",
"comments": 0,
"user": null,
"comments_url": "https://api.github.com/gists/96c9805268c8155af7ed33b2cc267715/comments",
"truncated": false
},
  {
"url": "https://api.github.com/gists/fcb5e5983fb016e5d07bf12373214cd8",
"forks_url": "https://api.github.com/gists/fcb5e5983fb016e5d07bf12373214cd8/forks",
"commits_url": "https://api.github.com/gists/fcb5e5983fb016e5d07bf12373214cd8/commits",
"id": "fcb5e5983fb016e5d07bf12373214cd8",
"git_pull_url": "https://gist.github.com/fcb5e5983fb016e5d07bf12373214cd8.git",
"git_push_url": "https://gist.github.com/fcb5e5983fb016e5d07bf12373214cd8.git",
"html_url": "https://gist.github.com/fcb5e5983fb016e5d07bf12373214cd8",
"files": {
"Скачать бесплатно stalker epub.md": {
"filename": "Скачать бесплатно stalker epub.md",
"type": "text/plain",
"language": "Markdown",
"raw_url": "https://gist.githubusercontent.com/anonymous/fcb5e5983fb016e5d07bf12373214cd8/raw/1958c1864cc35c3827fdae399ec1ce124d24e7e4/%D0%A1%D0%BA%D0%B0%D1%87%D0%B0%D1%82%D1%8C%20%D0%B1%D0%B5%D1%81%D0%BF%D0%BB%D0%B0%D1%82%D0%BD%D0%BE%20stalker%20epub.md",
"size": 5517
}
},
"public": true,
"created_at": "2017-06-13T12:16:13Z",
"updated_at": "2017-06-13T12:16:13Z",
"description": "Скачать бесплатно stalker epub",
"comments": 0,
"user": null,
"comments_url": "https://api.github.com/gists/fcb5e5983fb016e5d07bf12373214cd8/comments",
"truncated": false
},
```
### GET https://api.github.com/rate_limit
```json
{
"resources": {
"core": {
"limit": 5000,
"remaining": 4967,
"reset": 1497358854
},
"search": {
"limit": 30,
"remaining": 30,
"reset": 1497356320
},
"graphql": {
"limit": 5000,
"remaining": 5000,
"reset": 1497359860
}
},
"rate": {
"limit": 5000,
"remaining": 4967,
"reset": 1497358854
}
}
```
### GET https://api.github.com/repos/susruthi/susruthi_repo (https://api.github.com/repos/{owner}/{repo})
```json
{
"id": 93762516,
"name": "susruthi_repo",
"full_name": "Susruthi/susruthi_repo",
"owner": {
"login": "Susruthi",
"id": 29282131,
"avatar_url": "https://avatars3.githubusercontent.com/u/29282131?v=3",
"gravatar_id": "",
"url": "https://api.github.com/users/Susruthi",
"html_url": "https://github.com/Susruthi",
"followers_url": "https://api.github.com/users/Susruthi/followers",
"following_url": "https://api.github.com/users/Susruthi/following{/other_user}",
"gists_url": "https://api.github.com/users/Susruthi/gists{/gist_id}",
"starred_url": "https://api.github.com/users/Susruthi/starred{/owner}{/repo}",
"subscriptions_url": "https://api.github.com/users/Susruthi/subscriptions",
"organizations_url": "https://api.github.com/users/Susruthi/orgs",
"repos_url": "https://api.github.com/users/Susruthi/repos",
"events_url": "https://api.github.com/users/Susruthi/events{/privacy}",
"received_events_url": "https://api.github.com/users/Susruthi/received_events",
"type": "User",
"site_admin": false
},
"private": false,
"html_url": "https://github.com/Susruthi/susruthi_repo",
"description": null,
"fork": false,
"url": "https://api.github.com/repos/Susruthi/susruthi_repo",
"forks_url": "https://api.github.com/repos/Susruthi/susruthi_repo/forks",
"keys_url": "https://api.github.com/repos/Susruthi/susruthi_repo/keys{/key_id}",
"collaborators_url": "https://api.github.com/repos/Susruthi/susruthi_repo/collaborators{/collaborator}",
"teams_url": "https://api.github.com/repos/Susruthi/susruthi_repo/teams",
"hooks_url": "https://api.github.com/repos/Susruthi/susruthi_repo/hooks",
"issue_events_url": "https://api.github.com/repos/Susruthi/susruthi_repo/issues/events{/number}",
"events_url": "https://api.github.com/repos/Susruthi/susruthi_repo/events",
"assignees_url": "https://api.github.com/repos/Susruthi/susruthi_repo/assignees{/user}",
"branches_url": "https://api.github.com/repos/Susruthi/susruthi_repo/branches{/branch}",
"tags_url": "https://api.github.com/repos/Susruthi/susruthi_repo/tags",
"blobs_url": "https://api.github.com/repos/Susruthi/susruthi_repo/git/blobs{/sha}",
"git_tags_url": "https://api.github.com/repos/Susruthi/susruthi_repo/git/tags{/sha}",
"git_refs_url": "https://api.github.com/repos/Susruthi/susruthi_repo/git/refs{/sha}",
"trees_url": "https://api.github.com/repos/Susruthi/susruthi_repo/git/trees{/sha}",
"statuses_url": "https://api.github.com/repos/Susruthi/susruthi_repo/statuses/{sha}",
"languages_url": "https://api.github.com/repos/Susruthi/susruthi_repo/languages",
"stargazers_url": "https://api.github.com/repos/Susruthi/susruthi_repo/stargazers",
"contributors_url": "https://api.github.com/repos/Susruthi/susruthi_repo/contributors",
"subscribers_url": "https://api.github.com/repos/Susruthi/susruthi_repo/subscribers",
"subscription_url": "https://api.github.com/repos/Susruthi/susruthi_repo/subscription",
"commits_url": "https://api.github.com/repos/Susruthi/susruthi_repo/commits{/sha}",
"git_commits_url": "https://api.github.com/repos/Susruthi/susruthi_repo/git/commits{/sha}",
"comments_url": "https://api.github.com/repos/Susruthi/susruthi_repo/comments{/number}",
"issue_comment_url": "https://api.github.com/repos/Susruthi/susruthi_repo/issues/comments{/number}",
"contents_url": "https://api.github.com/repos/Susruthi/susruthi_repo/contents/{+path}",
"compare_url": "https://api.github.com/repos/Susruthi/susruthi_repo/compare/{base}...{head}",
"merges_url": "https://api.github.com/repos/Susruthi/susruthi_repo/merges",
"archive_url": "https://api.github.com/repos/Susruthi/susruthi_repo/{archive_format}{/ref}",
"downloads_url": "https://api.github.com/repos/Susruthi/susruthi_repo/downloads",
"issues_url": "https://api.github.com/repos/Susruthi/susruthi_repo/issues{/number}",
"pulls_url": "https://api.github.com/repos/Susruthi/susruthi_repo/pulls{/number}",
"milestones_url": "https://api.github.com/repos/Susruthi/susruthi_repo/milestones{/number}",
"notifications_url": "https://api.github.com/repos/Susruthi/susruthi_repo/notifications{?since,all,participating}",
"labels_url": "https://api.github.com/repos/Susruthi/susruthi_repo/labels{/name}",
"releases_url": "https://api.github.com/repos/Susruthi/susruthi_repo/releases{/id}",
"deployments_url": "https://api.github.com/repos/Susruthi/susruthi_repo/deployments",
"created_at": "2017-06-08T15:02:41Z",
"updated_at": "2017-06-08T15:02:41Z",
"pushed_at": "2017-06-08T15:02:41Z",
"git_url": "git://github.com/Susruthi/susruthi_repo.git",
"ssh_url": "git@github.com:Susruthi/susruthi_repo.git",
"clone_url": "https://github.com/Susruthi/susruthi_repo.git",
"svn_url": "https://github.com/Susruthi/susruthi_repo",
"homepage": null,
"size": 0,
"stargazers_count": 0,
"watchers_count": 0,
"language": null,
"has_issues": true,
"has_projects": true,
"has_downloads": true,
"has_wiki": true,
"has_pages": false,
"forks_count": 0,
"mirror_url": null,
"open_issues_count": 0,
"forks": 0,
"open_issues": 0,
"watchers": 0,
"default_branch": "master",
"permissions": {
"admin": true,
"push": true,
"pull": true
},
"allow_squash_merge": true,
"allow_merge_commit": true,
"allow_rebase_merge": true,
"network_count": 0,
"subscribers_count": 0
}
```
### GET https://api.github.com/search/repositories?q={query}{&page,per_page,sort,order} (repo_searh_url)

### GET https://api.github.com/gists/starred

### GET https://api.github.com/user/orgs  (user_organizations_url)

### GET https://api.github.com/users/{user}/repos{?type,page,per_page,sort} (user_repositories_url)
```json
{
"id": 88580457,
"name": "angular-2",
"full_name": "Ram0912/angular-2",
"owner": {
"login": "Ram0912",
"id": 22836667,
"avatar_url": "https://avatars0.githubusercontent.com/u/22836667?v=3",
"gravatar_id": "",
"url": "https://api.github.com/users/Ram0912",
"html_url": "https://github.com/Ram0912",
"followers_url": "https://api.github.com/users/Ram0912/followers",
"following_url": "https://api.github.com/users/Ram0912/following{/other_user}",
"gists_url": "https://api.github.com/users/Ram0912/gists{/gist_id}",
"starred_url": "https://api.github.com/users/Ram0912/starred{/owner}{/repo}",
"subscriptions_url": "https://api.github.com/users/Ram0912/subscriptions",
"organizations_url": "https://api.github.com/users/Ram0912/orgs",
"repos_url": "https://api.github.com/users/Ram0912/repos",
"events_url": "https://api.github.com/users/Ram0912/events{/privacy}",
"received_events_url": "https://api.github.com/users/Ram0912/received_events",
"type": "User",
"site_admin": false
},
"private": false,
"html_url": "https://github.com/Ram0912/angular-2",
"description": "sample apllication",
"fork": false,
"url": "https://api.github.com/repos/Ram0912/angular-2",
"forks_url": "https://api.github.com/repos/Ram0912/angular-2/forks",
"keys_url": "https://api.github.com/repos/Ram0912/angular-2/keys{/key_id}",
"collaborators_url": "https://api.github.com/repos/Ram0912/angular-2/collaborators{/collaborator}",
"teams_url": "https://api.github.com/repos/Ram0912/angular-2/teams",
"hooks_url": "https://api.github.com/repos/Ram0912/angular-2/hooks",
"issue_events_url": "https://api.github.com/repos/Ram0912/angular-2/issues/events{/number}",
"events_url": "https://api.github.com/repos/Ram0912/angular-2/events",
"assignees_url": "https://api.github.com/repos/Ram0912/angular-2/assignees{/user}",
"branches_url": "https://api.github.com/repos/Ram0912/angular-2/branches{/branch}",
"tags_url": "https://api.github.com/repos/Ram0912/angular-2/tags",
"blobs_url": "https://api.github.com/repos/Ram0912/angular-2/git/blobs{/sha}",
"git_tags_url": "https://api.github.com/repos/Ram0912/angular-2/git/tags{/sha}",
"git_refs_url": "https://api.github.com/repos/Ram0912/angular-2/git/refs{/sha}",
"trees_url": "https://api.github.com/repos/Ram0912/angular-2/git/trees{/sha}",
"statuses_url": "https://api.github.com/repos/Ram0912/angular-2/statuses/{sha}",
"languages_url": "https://api.github.com/repos/Ram0912/angular-2/languages",
"stargazers_url": "https://api.github.com/repos/Ram0912/angular-2/stargazers",
"contributors_url": "https://api.github.com/repos/Ram0912/angular-2/contributors",
"subscribers_url": "https://api.github.com/repos/Ram0912/angular-2/subscribers",
"subscription_url": "https://api.github.com/repos/Ram0912/angular-2/subscription",
"commits_url": "https://api.github.com/repos/Ram0912/angular-2/commits{/sha}",
"git_commits_url": "https://api.github.com/repos/Ram0912/angular-2/git/commits{/sha}",
"comments_url": "https://api.github.com/repos/Ram0912/angular-2/comments{/number}",
"issue_comment_url": "https://api.github.com/repos/Ram0912/angular-2/issues/comments{/number}",
"contents_url": "https://api.github.com/repos/Ram0912/angular-2/contents/{+path}",
"compare_url": "https://api.github.com/repos/Ram0912/angular-2/compare/{base}...{head}",
"merges_url": "https://api.github.com/repos/Ram0912/angular-2/merges",
"archive_url": "https://api.github.com/repos/Ram0912/angular-2/{archive_format}{/ref}",
"downloads_url": "https://api.github.com/repos/Ram0912/angular-2/downloads",
"issues_url": "https://api.github.com/repos/Ram0912/angular-2/issues{/number}",
"pulls_url": "https://api.github.com/repos/Ram0912/angular-2/pulls{/number}",
"milestones_url": "https://api.github.com/repos/Ram0912/angular-2/milestones{/number}",
"notifications_url": "https://api.github.com/repos/Ram0912/angular-2/notifications{?since,all,participating}",
"labels_url": "https://api.github.com/repos/Ram0912/angular-2/labels{/name}",
"releases_url": "https://api.github.com/repos/Ram0912/angular-2/releases{/id}",
"deployments_url": "https://api.github.com/repos/Ram0912/angular-2/deployments",
"created_at": "2017-04-18T04:10:26Z",
"updated_at": "2017-04-18T04:10:26Z",
"pushed_at": "2017-05-02T10:16:58Z",
"git_url": "git://github.com/Ram0912/angular-2.git",
"ssh_url": "git@github.com:Ram0912/angular-2.git",
"clone_url": "https://github.com/Ram0912/angular-2.git",
"svn_url": "https://github.com/Ram0912/angular-2",
"homepage": null,
"size": 1,
"stargazers_count": 0,
"watchers_count": 0,
"language": null,
"has_issues": true,
"has_projects": true,
"has_downloads": true,
"has_wiki": true,
"has_pages": false,
"forks_count": 0,
"mirror_url": null,
"open_issues_count": 0,
"forks": 0,
"open_issues": 0,
"watchers": 0,
"default_branch": "master",
"permissions": {
"admin": false,
"push": false,
"pull": true
}
},
  {
"id": 71247963,
"name": "ArtZone",
"full_name": "Ram0912/ArtZone",
"owner": {
"login": "Ram0912",
"id": 22836667,
"avatar_url": "https://avatars0.githubusercontent.com/u/22836667?v=3",
"gravatar_id": "",
"url": "https://api.github.com/users/Ram0912",
"html_url": "https://github.com/Ram0912",
"followers_url": "https://api.github.com/users/Ram0912/followers",
"following_url": "https://api.github.com/users/Ram0912/following{/other_user}",
"gists_url": "https://api.github.com/users/Ram0912/gists{/gist_id}",
"starred_url": "https://api.github.com/users/Ram0912/starred{/owner}{/repo}",
"subscriptions_url": "https://api.github.com/users/Ram0912/subscriptions",
"organizations_url": "https://api.github.com/users/Ram0912/orgs",
"repos_url": "https://api.github.com/users/Ram0912/repos",
"events_url": "https://api.github.com/users/Ram0912/events{/privacy}",
"received_events_url": "https://api.github.com/users/Ram0912/received_events",
"type": "User",
"site_admin": false
},
"private": false,
"html_url": "https://github.com/Ram0912/ArtZone",
"description": null,
"fork": false,
"url": "https://api.github.com/repos/Ram0912/ArtZone",
"forks_url": "https://api.github.com/repos/Ram0912/ArtZone/forks",
"keys_url": "https://api.github.com/repos/Ram0912/ArtZone/keys{/key_id}",
"collaborators_url": "https://api.github.com/repos/Ram0912/ArtZone/collaborators{/collaborator}",
"teams_url": "https://api.github.com/repos/Ram0912/ArtZone/teams",
"hooks_url": "https://api.github.com/repos/Ram0912/ArtZone/hooks",
"issue_events_url": "https://api.github.com/repos/Ram0912/ArtZone/issues/events{/number}",
"events_url": "https://api.github.com/repos/Ram0912/ArtZone/events",
"assignees_url": "https://api.github.com/repos/Ram0912/ArtZone/assignees{/user}",
"branches_url": "https://api.github.com/repos/Ram0912/ArtZone/branches{/branch}",
"tags_url": "https://api.github.com/repos/Ram0912/ArtZone/tags",
"blobs_url": "https://api.github.com/repos/Ram0912/ArtZone/git/blobs{/sha}",
"git_tags_url": "https://api.github.com/repos/Ram0912/ArtZone/git/tags{/sha}",
"git_refs_url": "https://api.github.com/repos/Ram0912/ArtZone/git/refs{/sha}",
"trees_url": "https://api.github.com/repos/Ram0912/ArtZone/git/trees{/sha}",
"statuses_url": "https://api.github.com/repos/Ram0912/ArtZone/statuses/{sha}",
"languages_url": "https://api.github.com/repos/Ram0912/ArtZone/languages",
"stargazers_url": "https://api.github.com/repos/Ram0912/ArtZone/stargazers",
"contributors_url": "https://api.github.com/repos/Ram0912/ArtZone/contributors",
"subscribers_url": "https://api.github.com/repos/Ram0912/ArtZone/subscribers",
"subscription_url": "https://api.github.com/repos/Ram0912/ArtZone/subscription",
"commits_url": "https://api.github.com/repos/Ram0912/ArtZone/commits{/sha}",
"git_commits_url": "https://api.github.com/repos/Ram0912/ArtZone/git/commits{/sha}",
"comments_url": "https://api.github.com/repos/Ram0912/ArtZone/comments{/number}",
"issue_comment_url": "https://api.github.com/repos/Ram0912/ArtZone/issues/comments{/number}",
"contents_url": "https://api.github.com/repos/Ram0912/ArtZone/contents/{+path}",
"compare_url": "https://api.github.com/repos/Ram0912/ArtZone/compare/{base}...{head}",
"merges_url": "https://api.github.com/repos/Ram0912/ArtZone/merges",
"archive_url": "https://api.github.com/repos/Ram0912/ArtZone/{archive_format}{/ref}",
"downloads_url": "https://api.github.com/repos/Ram0912/ArtZone/downloads",
"issues_url": "https://api.github.com/repos/Ram0912/ArtZone/issues{/number}",
"pulls_url": "https://api.github.com/repos/Ram0912/ArtZone/pulls{/number}",
"milestones_url": "https://api.github.com/repos/Ram0912/ArtZone/milestones{/number}",
"notifications_url": "https://api.github.com/repos/Ram0912/ArtZone/notifications{?since,all,participating}",
"labels_url": "https://api.github.com/repos/Ram0912/ArtZone/labels{/name}",
"releases_url": "https://api.github.com/repos/Ram0912/ArtZone/releases{/id}",
"deployments_url": "https://api.github.com/repos/Ram0912/ArtZone/deployments",
"created_at": "2016-10-18T12:53:18Z",
"updated_at": "2016-10-31T13:35:53Z",
"pushed_at": "2017-01-30T10:09:14Z",
"git_url": "git://github.com/Ram0912/ArtZone.git",
"ssh_url": "git@github.com:Ram0912/ArtZone.git",
"clone_url": "https://github.com/Ram0912/ArtZone.git",
"svn_url": "https://github.com/Ram0912/ArtZone",
"homepage": null,
"size": 9236,
"stargazers_count": 0,
"watchers_count": 0,
"language": "Java",
"has_issues": true,
"has_projects": true,
"has_downloads": true,
"has_wiki": true,
"has_pages": false,
"forks_count": 0,
"mirror_url": null,
"open_issues_count": 0,
"forks": 0,
"open_issues": 0,
"watchers": 0,
"default_branch": "master",
"permissions": {
"admin": false,
"push": false,
"pull": true
}
},
```

https://blogs.infosupport.com/accessing-githubs-rest-api-with-curl/
