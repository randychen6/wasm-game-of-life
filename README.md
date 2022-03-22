1, run script "cargo generate --git https://github.com/rustwasm/wasm-pack-template" to generate rust Wasm template project on your computer.

2, Run script "wasm-pack build" to build project and generate a directory named "pkg" containing generated files which will be imported to javascript

3,  Rebuild project using script "wasm-pack build" when you do any modification on rust code afterwards. 

4, Restart web server using command "nom run start" when you do any modification on javascript code.

5, Run script "wasm-pack test --chrome --headless" to generate test directory.
