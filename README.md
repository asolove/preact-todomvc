# Todo CRDT

An in-development experiment with the classic todos app: offline & collaborative editing using CRDTs.

## Progress

- [X] Use Preact TodoMVC implementation for view layer and model interface.
- [X] Add ServiceWorker so the app works offline
- [ ] Replace model layer with CRDTs
- [ ] Synchronize changes across clients with Lasp backend.
- [ ] Enforce weak invariant from backend in frontend model.

## Acknowledgements

- Thanks to the [TodoMVC project](http://todomvc.com) for the original idea and shared images and styles.
- THanks to @developit's [TodoMVC Preact implementation](https://github.com/developit/preact-todomvc) for the original implementation of the view layer.
