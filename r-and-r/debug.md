# debug

```diff
+ thing
- thing
* thing
> thing
< thing
```

```yaml
test: 1
test:
  some text
  - a bullet
try_this: here
```

{% hint style="info" %}
test
{% endhint %}

{% api-method method="get" host="things" path="" %}
{% api-method-summary %}
api test
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="thing test" type="number" required=true %}
desc
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
example name
{% endapi-method-response-example-description %}

```text
text
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% tabs %}
{% tab title="First Tab" %}
dont click tab!
{% endtab %}
{% endtabs %}

