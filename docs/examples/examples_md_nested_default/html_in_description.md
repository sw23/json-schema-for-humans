# HTML in descriptions

- [1. [Optional] Property HTML in descriptions > raw_html](#raw_html)
- [2. [Optional] Property HTML in descriptions > html_in_markdown](#html_in_markdown)
- [3. [Optional] Property HTML in descriptions > json_in_markdown](#json_in_markdown)

**Title:** HTML in descriptions

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

<details>
<summary>
<strong> <a name="raw_html"></a>1. [Optional] Property HTML in descriptions > raw_html</strong>  

</summary>
<blockquote>

**Title:** Some raw HTML

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

**Description:** <br/><br/><br/><br/><a href="https://example.com">A link to example.com</a>

</blockquote>
</details>

<details>
<summary>
<strong> <a name="html_in_markdown"></a>2. [Optional] Property HTML in descriptions > html_in_markdown</strong>  

</summary>
<blockquote>

**Title:** Some HTML in Markdown

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

**Description:** Here is some HTML:
```html
<br/><br/><br/><br/><a href="https://example.com">A link to example.com</a>
```

</blockquote>
</details>

<details>
<summary>
<strong> <a name="json_in_markdown"></a>3. [Optional] Property HTML in descriptions > json_in_markdown</strong>  

</summary>
<blockquote>

**Title:** Some JSON in Markdown

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

**Description:** Here is some JSON:
```json
{
  "property": "value"
}
```

</blockquote>
</details>

----------------------------------------------------------------------------------------------------------------------------
Generated using [json-schema-for-humans](https://github.com/coveooss/json-schema-for-humans)