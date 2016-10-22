# PunchUp
**(NOTE: Currently in planning stage. We are looking for contributors.)** An open-source modular rapid application builder and content management system. PunchUp is open-source using the permissive GPLv3 license.  PunchUp's core operates alone or with add-on modules. The framework is a combination of a RAD drag-n-drop application builder and a web content managment system. 

## The PunchUp Core Structure
The core of PunchUp is made of two parts; (1) a [server-side](https://en.wikipedia.org/wiki/Server-side) [API](https://en.wikipedia.org/wiki/Application_programming_interface) layer and (2) a [Javascript](https://en.wikipedia.org/wiki/JavaScript) and [HTML5](https://en.wikipedia.org/wiki/HTML5) [front-end](https://en.wikipedia.org/wiki/Front_and_back_ends).

### (1) The PunchUp API
The PunchUp API is written in [PHP](https://en.wikipedia.org/wiki/PHP) and makes use of the [Lumen](https://github.com/laravel/lumen) [framework](https://en.wikipedia.org/wiki/Web_framework). It is a [JSON](http://www.json.org/) [REST](https://en.wikipedia.org/wiki/Representational_state_transfer) based API. In addition to responding to [JSON requests](http://www.json.org/JSONRequest.html), the API connects to various types of [data sources](https://en.wikipedia.org/wiki/Data_source), such as [MySQL](http://www.mysql.com/), [MSSQL](https://en.wikipedia.org/wiki/Microsoft_SQL_Server), [SQLite](https://sqlite.org/), [MongoDB](https://www.mongodb.com/), and [flat-file](https://en.wikipedia.org/wiki/Flat_file_database) [databases](https://en.wikipedia.org/wiki/Database). A unique feature of the API is how it automattically generates new database [models](https://en.wikipedia.org/wiki/Database_model), REST [endpoints](https://github.com/Mach-II/Mach-II-Framework/wiki/Introduction-to-REST-Endpoints) and [CRUD](https://en.wikipedia.org/wiki/Create,_read,_update_and_delete) based [routes](https://laravel.com/docs/5.3/routing). 

### (2) The PunchUp Front-End
The Punchup Front-End is written in HTML5, [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets) and Javascript and makes use of the [Bootstrap](http://getbootstrap.com/) 3 front-end framework and the [Sass](http://sass-lang.com/) [preprocessor](https://en.wikipedia.org/wiki/Preprocessor). A Javascript framework has not been chosen yet. It is important that one be selected because the design of PunchUp is a highly [opinionated](https://en.wikipedia.org/wiki/Convention_over_configuration).

## Contributing
Please contact [Kevin Young](https://github.com/rdytogokev) to inquire about contributing. We are looking for every type of contributor.

## Languages
[PHP >= 7.0](http://php.net/)

[Javascript (ECMAScript) >= 6.0](https://en.wikipedia.org/wiki/JavaScript)

## License
PunchUp is open-sourced software licensed under the [GNU GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html)
