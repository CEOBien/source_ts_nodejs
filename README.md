<H1>Cấu trúc thư mục</H1>
<div>dist: Thư mục chứa các file build</div>
<div>src: Thư mục chứa mã nguồn</div>
<div>src/constants: Chứa các file chứa các hằng số</div>
<div>src/middlewares: Chứa các file chứa các hàm xử lý middleware, như validate, check token, ...</div>
<div>src/controllers: Chứa các file nhận request, gọi đến service để xử lý logic nghiệp vụ, trả về response</div>
<div>src/services: Chứa các file chứa method gọi đến database để xử lý logic nghiệp vụ</div>
<div>src/models: Chứa các file chứa các model</div>
<div>src/routes: Chứa các file chứa các route</div>
<div>src/utils: Chứa các file chứa các hàm tiện ích, như mã hóa, gửi email, ...</div>

<h2>Lệnh chạy dư án</h2>
<b>npm run dev</b>
<p>dung để chạy ở môi trường dev</p>
================================================================
<h3>Dùng để build và chạy dự án khi hoàn thành</h3>
<p>npm run build</p>
<p>npm run start</p>
<h3>Câu lệnh này sẽ giúp bạn kiểm tra lỗi ESLint trong dự án</h3>
<p>npm run lint</p>
<h3>Nếu bạn muốn ESLint tự động fix lỗi thì chạy câu lệnh sau</h3>
<p>npm run lint:fix
</p>
<h3>Tương tự với Prettier, ta có câu lệnh</h3>
<p>npm run prettier</p>

<b>Lưu ý cài thêm gói @types/ten-thu-vien nếu cần
Vì đây là dự án chạy với Typescript nên khi cài đặt bất cứ một thư viện này chúng ta nên xem thư viện đó có hỗ trợ TypeScript không nhé. 
Có một số thư viện ở npm hỗ trợ TypeScript sẵn, có một số thì chúng ta phải cài thêm bộ TypeScript của chúng qua @types/ten-thu-vien

Ví dụ như express thì chúng ta cài như sau </b>
<p>npm i express
npm i @types/express -D
</p>
