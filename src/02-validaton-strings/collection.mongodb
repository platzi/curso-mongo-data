use("platzi_store")

db.createCollection('users', {
    validator: {
        $jsonSchema: {
            bsonType: 'object',
            required: ['email', 'password'],
            properties: {
                name: {
                    bsonType: 'string'
                },
                last_name: {
                    bsonType: 'string'
                },
                email: {
                    bsonType: 'string'
                },
                password: {
                    bsonType: 'string'
                },
            }
        }
    }
})