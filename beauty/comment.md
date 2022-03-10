### 发布评论

##### HTTP Method: POST
##### URL: https://host/app/beauty/comment.php

#####  Parameters
名称|格式|描述|必须|默认值
---|---|---|---|---
公共参数||||
topic_id    | int       | 动态id    | true |
content     | string    | 内容      | true |

##### HTTP Response
```json
{
	'code': 200,
	'data': {
		'count_comment': 1,
		'comment': comment_info
	},
	'desc': ''
}
```
[comment_info](entity_comment_info.md)
```json
{
	'code': 200,
	'data': {
		'count_comment': 1,
		'comment': {
			'topic_id': 123,
			'uid': 1764593,
			'content': 'comment-1646898758',
			't_create': 1646898759,
			'reported': 0,
			'id': '19'
		}
	},
	'desc': ''
}
```