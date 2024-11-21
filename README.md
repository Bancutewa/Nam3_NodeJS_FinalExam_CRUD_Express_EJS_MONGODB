# Cách chạy dự án
## B1: vào file config/db.js

const mongoose = require('mongoose');
const connectDB = async () => {
  try {
    mongoose.set('strictQuery', false);
    const conn = await mongoose.connect( Nhập DB ở chỗ này );
    console.log(`Database Connected: ${conn.connection.host}`);
  } catch (error) {
    console.log(error);
  }
}
module.exports = connectDB;

## B2: 
Nhập lệnh npm ii
Sau đó nhập npm start là được
