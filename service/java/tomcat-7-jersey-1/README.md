# Jersey 1.x on Tomcat 7

mvn tomcat7:run

You can then see:

- Root listing at: [http://localhost:9090/api-docs](http://localhost:9090/api-docs)
- Pet resource listing at [http://localhost:9090/api-docs/pet](http://localhost:9090/api-docs/pet)
- User resource listing at [http://localhost:9090/api-docs/user](http://localhost:9090/api-docs/user)
- /store is behing API key auth here. So by suffixing `api_key=special-key` you can see:
  - In root listing see /store API via [http://localhost:9090/api-docs?api_key=special-key](http://localhost:9090/api-docs?api_key=special-key)
  - Access /store API listing via [http://localhost:9090/api-docs/store?api_key=special-key](http://localhost:9090/api-docs/store?api_key=special-key)

