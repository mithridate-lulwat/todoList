# TodoList

This is a Todo list app that allows for adding tasks to a list, deleting and
editing them. 
It is built using a local web server, and is an exercise to test my understanding
of the http and html/template packages in Golang. 

# Usage :
On Unix :  
```
go build todo.go
./todo 
```
Functions : 
- Seeing the tasklist : 

    [http://localhost:8080/](http://localhost:8080/)
     
- Adding a task : 

    [http://localhost:8080/add/](http://localhost:8080/)

    

Todo :
- [x] Display only non-empty fields
- [x] Date and time handling
- [ ] Add input checking
- [x] Add "add" button
- [ ] Prettier UI
- [ ] Editing tasks
- [x] Deleting tasks



