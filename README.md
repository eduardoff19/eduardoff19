window.Store.Chat._find = e => {
const target = window.Store.Chat.get(e)
return target ? Promise.resolve(target) : Promise.resolve({
id: e
})
}

must include this line 👆
