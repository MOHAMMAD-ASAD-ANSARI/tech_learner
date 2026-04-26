Today  i m very happy to share i somehow am able to connect what i learned in os and coa as a subject of btech computer engg 

my laptop is capable of storing path address of file of size more than 250 chars

but when i was downloading jupyter on my pc it shows up an error

ERROR: Could not install packages due to an OSError: [Errno 2] No such file or directory: 'C:\\Users\\MOHAMMAD ASAD\\AppData\\Local\\Programs\\Python\\Python310\\share\\jupyter\\labextensions\\@jupyter-widgets\\jupyterlab-manager\\static\\vendors-node_modules_d3-color_src_color_js-node_modules_d3-format_src_defaultLocale_js-node_m-09b215.2643c43f22ad111f4f82.js.map' HINT: This error might have occurred since this system does not have Windows Long Path support enabled. You can find information on how to enable this at https://pip.pypa.io/warnings/enable-long-paths

it says os is restricting storing path size more than 250 char so need to enable it some or other way

thrn  i got to know how system works that there are 3 leveels application level , os level, coa level

in my case coa leel is all good i need to enable long path size in os level so went through system like a hacker and enable it and booom it works


i m really very fascinatd knowing this


i also learned how asynclocalstorage work
Class: AsyncLocalStorage
new AsyncLocalStorage([options])
Static method: AsyncLocalStorage.bind(fn)
Static method: AsyncLocalStorage.snapshot()
asyncLocalStorage.disable()
asyncLocalStorage.getStore()
asyncLocalStorage.enterWith(store)
asyncLocalStorage.name
asyncLocalStorage.run(store, callback[, ...args])
asyncLocalStorage.exit(callback[, ...args])
asyncLocalStorage.withScope(store)
Usage with async/await
its reallife usecase is logging.
