# settings:set
Drupal Console कॉन्फिग फाइलमध्ये विशिष्ट सेटिंग मूल्य बदला.

**वापर:**
```
drupal settings:set [arguments] [options]
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--help | Display this help message
--quiet | Do not output any message
--verbose | Increase the verbosity of messages: 1 for normal output, 2 for more verbose output and 3 for debug
--version | Display this application version
--ansi | Force ANSI output
--no-ansi | Disable ANSI output
--no-interaction | Do not ask any interactive question
--env | The Environment name
--root | Define the Drupal root to be used in command execution
--debug | Switches on debug mode
--learning | Generate a verbose code output
--generate-chain | Shows command options and arguments as yaml output to be used in chain command
--generate-inline | Shows command options and arguments as inline command
--generate-doc | Shows command options and arguments as markdown
--target | Site name you want to interact with (for local or remote sites)
--uri | URI of the Drupal site to use (for multi-site environments or when running on an alternate port)
--yes | Skip confirmation and proceed

## उपलब्ध वितर्क
वितर्क | तपशील
---------|-------------
command | The command to execute
name | Drupal Console कॉन्फिग फाइलमध्ये मूल्य सेट करण्यासाठी YAML मध्ये नाव सेट करणे फॅंटन स्वरूप.
value | मूल्य Drupal Console कॉन्फिग फाइलमध्ये सेट करणे.

## उदाहरणे
* अनुप्रयोग भाषा सेटिंग मूल्य "%s" वर सेट करा.
```
drupal settings:set  application.language es
```
