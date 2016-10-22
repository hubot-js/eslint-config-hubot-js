# eslint-config-hubot-js

[![npm](https://img.shields.io/npm/v/eslint-config-hubot-js.svg)](https://www.npmjs.com/package/eslint-config-hubot-js)
[![dependencies-badge](https://david-dm.org/eslint-config-hubot-js/hubot.js.svg)](https://david-dm.org/eslint-config-hubot-js/eslint-config-hubot-js)  [![devDependencies Status](https://david-dm.org/eslint-config-hubot-js/eslint-config-hubot-js/dev-status.svg)](https://david-dm.org/eslint-config-hubot-js/eslint-config-hubot-js?type=dev)

> Eslint for Hubot.js projects

## Usage

This is a [Eslint](http://eslint.org/) setting made for [hubot.js](https://github.com/hubot-js/hubot.js) and its [auxiliary projects](https://github.com/hubot-js). It extends the great [airbnb configuration](https://www.npmjs.com/package/eslint-config-airbnb) modifying some rules.

To use this setting your project you must have eslint as a [dependency in your project or instaled globally](http://eslint.org/docs/user-guide/getting-started). In addition a .eslintrc.json file must be created to extend this setting. See the example:

```
{
  "extends": "hubot-js"  
}
```

After that you can run the eslint with the command:

```
eslint .
```

Or integrate it with your [text editor](http://eslint.org/docs/user-guide/integrations):

![eslint-text-editor-example](https://s22.postimg.org/8pnm0q49d/eslint_text_editor_example.jpg)


If you have questions use the [hubot.js project](https://github.com/hubot-js/hubot.js) as an example, or open an [issue](https://github.com/robsonbittencourt/eslint-config-hubot-js/issues).