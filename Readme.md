i used these in graphiql
# mutation {
#   addUser(name:"rania", email:"test@test.tn", password:"test"){
#     id
#     name
#     email
#     password
#   }
# }

# query{user(id:2){
#   name
#   email
# }}

# query{users{
#   name
#   email
# }}

# mutation{
#   deleteUser(id:1){
#     name
#   }
# }

# mutation{
  
#   updateUser(id:2,name: "test update",email:"test@rest.tn",password:"test"){
#     name
#     email
#   }
# }