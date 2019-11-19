# mutation-testing-with-stryker-javascript

1. Faça download deste projeto (zip ou git clone)
2. Instale o stryker-cli: `npm install -g stryker-cli`
3. Configure o stryker no projeto: `stryker init`

Responda as perguntas que serão exibidas conforme abaixo:

- ? **Are you using one of these frameworks? Then select a preset configuration.** None/other
- ? **Which test runner do you want to use? If your test runner isn't listed here, you can choose "command" (it uses your `npm test` command, but will come with a big performance penalty)** karma
- ? **Which test framework do you want to use?** jasmine
- ? **What kind of code do you want to mutate?** javascript
- ? **[optional] What kind transformations should be applied to your code?** 
- ? **Which reporter(s) do you want to use?** html, clear-text, progress
- ? **Which package manager do you want to use?** npm

4 . Após concluir a configuração, invoque os mutantes:
`stryker run`

*[That's all folks](https://stryker-mutator.io/ "That's all folks")*

-------

*Em construção*
