Digimaker is a Content Management Framework focusing on simplicity, flexibility and performance. 

Written in Golang.

<br />
<a href="https://digimaker.org/doc"><button class="btn btn-primary">Documentation</button></a>  &nbsp;&nbsp; <a href="https://github.com/digimakergo/digimaker">Github project</a>


<br /><br />

<a href="https://digimaker.org/dmeditor">DMEditor - a visual editor tool</a>

<a href="https://digimaker.org/doc/digimaker-ui">digimaker-ui(client library) documentation</a>

<br />

#### Complete components based
It's complete components based, both in server side and client side, both in end user and in editorial ui.

It means you own the app entry(in server it's the index page or main function, in client it's the App.tsx(React for instance)), also means the content management features can be well intergrated into your existing system.

#### Balanced content model design
Define your content model like object-oriented language's class in json, then it's can be used in backend, server api and rest api automatically.

You can still use ORM or sql to easily access the content data.

#### Beyond content
Typical content can be articles, documents, users, products, images&videos, also can be orders, subcriptions, which is mix of content and database table. From pure database's view, if you don't want to write input client, business logic for some table fields, digimaker can be useful here.

#### Flexible permission
Control your permission based on content types, under location, field value, etc. It supports attribute level permission, meaning some users can create/update some fields of content.

Variable support means you can define permission rules and set values in role content directly using editorial ui.

#### Log&Debug-able
You are able to see what's going on using logs/debug tools, from database query, to templates used, and permission policies. Good log&debug make development & maintaince easier.
