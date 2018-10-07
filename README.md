# herculesX
Simple, predictable, developer friendly state management for alipay mini-program


![setData (1).png](https://cdn.nlark.com/lark/0/2018/png/82549/1537904366328-49a7e2e5-5aeb-4326-be5f-8cf0eb603181.png) 

## Feature

- [x] Component, Page, global wrapper
- [x] vuex like apis and concept: actions, mutations, getters, plugins.
- [x] strengthen mutation, getters: add immutable helper, global power to getters.and improve mutation usecase, add some common innerMutation
- [x] plugins support, add logger as inner plugin
- [x] cross page communication: message channel, auto router dispatcher, getState by namespace...
- [x] cross components communication: support ref
- [x] connect: connect Page to Component, add mapStateToProps, mapGettersToProps...
- [x] global store support: manage all store, component instance and global state, global message bus ,event bus
- [x] event bus support
- [x] router: improve router usecase, auto router dispatcher, add resume lifecycle
- [x] use immer and immutable helper to promise immutable

## TODO
- [ ] doc & gitbook,github.io
- [ ] examples & boilerplate
- [ ] cli
- [ ] test-utils & mock helper
- [ ] dev-tools for ide, standalone
- [ ] modules (need deeply design)
- [ ] error catcher plugin
- [ ] refactory, separate appx data setter as independent repo
