 <details><summary><h2>CHAPTER 1: PYTHON LANGUAGE</h2></summary>

<details> 
<summary> BASIC SET UP</summary>

Các thao tác câu lệnh trên command window:
- khi gõ: python --version hay python -V sẽ hiện ra phiên bản được cài.
- cls: xoá các dòng hiện trên cmd.
- Để chuyển ổ đĩa `D:` or `C:`.
- Để chạy được file python trên cmd: `pthon main.py` theo đúng đường path chứa file python.
- `cd..` quay lại thư mục trước đó.
- Chỉ cần gõ hai từ đầu file sau đó nhấn `Tab` sẽ hoàn thiện tên thư mục.
- ghi python sẽ hiện interactive python như hoạt động trên python.
- file `.py` là file extension.
Các câu lệnh cơ bản của python:

</details>

</details>

##

<details> 
<summary> L01: BASIC PYTHON</summary>

### 1.Basic Python:

- cú pháp comment: `# comment`
- Tên biến : ` tên biến = giá trị`
Example:
    tuoi = 17;
    ten = "How Kream"
    Pi = 3.14
    Hoặc là: tuoi,ten,Pi = 17,"How Kream",3.14
- print(): in ra mang hinh
- Câu lệnh kiểm tra kiểu dữ liệu: `type(tuoi) or type(ten) `.
### 2. Các kiểu dữ liệu:

- Không cần khai báo kiểu dữ liệu với biến.
- Giá trị số nguyên và số thực sẽ rất lớn khác với từng giá trị của kiểu dữ liệu.
- Để sử dụng kiểu dữ liệu `Decimal` thì ta cần khai báo kiểu dữ liệu decimal.
- Từ thư viện `decimal` import tất cả mọi thứ vào.

Example 1:

 <img src="https://i.imgur.com/MUcd5vi.jpg">

- Để tạo một phân số trong python: `Fraction(6,9)` thì cần thêm thư viện: `from fractions import*` vào file.
- Sô phức: `c = complex(2,5)` muốn lấy giá trị:` print(c.real) or print(c.imag)`.
- 
**Các câu lệnh toán tử:**

<img src="https://i.imgur.com/vwwAaKX.jpg">

- Cách khai báo thư viện và sử dụng thư viện math. Ngoài ra có các hàm sử dụng trên thư viện math.

<img src="https://i.imgur.com/oS10IaV.jpg">

Example 2:

<img src="https://i.imgur.com/zCRA6pO.jpg">

</details>

##

<details> 
<summary> L02: TYPEDATA OF STRING</summary>

### 1. Kiểu string:

- Tất cả tên được nằm trong `'a'` or `" a "` or`''' a '''` or`""" a """` trong python đều sẽ là string.
- String nhiều dòng muốn xuống dòng thì ta dùng: `''' Quoc Phu  Free Education ..... jsaj'''` . Ngoài ra có thể dùng để làm comment `''' comment '''` or `""" comment """` khi nó không gán vào biến.
- Ngoài ra cũng có các ký tự đặc biệt `\n \t `

Bảng ký tự đặc biệt trong python:

<img src="https://i.imgur.com/JnbW7S6.jpg">

*Note*: print(r'Hiax, \n hello') khi có `r` sẽ cho chuỗi liền mạch và k thực hiện các ký tự đặc biệt.
- Cú pháp cộng hai chuỗi lại với nhau: ` strc = stra + strb` hoặc có thể tạo số lần lặp chuỗi `strc = 5*stra or 5*strb`
- Cú pháp tạo ra kiểm tra ký tụ trong chuối:`strc = strB in strA` kiểm tra ký tự của strb có trong stra hay không. nếu đúng trả lại `true` or `false` cho strc.
- Các phần tử trong chuỗi `strA = 'Quoc Phu'` thì sẽ có các index như trong array. Ví dụ: strA[0], strA[1] or  ngược lại phải sang trái thì bắt đầu từ: strA[-1], strA[-2].
- `len(stra)`  : độ dài của chuối ký tự.
- Cắt chuỗi: `strA[1 : len(stra)]` , `strA[1 : None]`  or ` strA[1 : 5]` không lấy ký tự vị trí đầu tiền và phần tử 5(index: 4). Cắt từ trái sang phải.
**Note**: Ép kiểu dữ liệu:

- `int("69") + 5 : ép kiểu từ string sang int` 
- `float("69")` or `int("6.9")` or` str(69) + "5"`.
- Muốn in ra mã file hex: `print(hash(stra))`
**Note** thay đổi 1 ký tự trong string.

<img src="https://i.imgur.com/xS01L48.jpg">

Example:

<img src="https://i.imgur.com/96YtG1M.jpg">

**Note** : Các cú pháp đặc biệt:
```py
a = 'Quoc Phu is %s' %('Phu')
print(a) 
```
- Nó sẽ thay thế 'Phu' cho `%s`.
- %s: là string.

```py
a = 'Quoc Phu is %s %s' %('1','3')
print(a) 
```

**fstring**:

<img src="https://i.imgur.com/sPeftKF.jpg">

<img src="https://i.imgur.com/dcNgFTX.jpg">

### 2.

</details>

##

</details>

<details><summary><h2>CHAPTER</h2></summary>

 ##

<details> 
<summary> L02: TYPEDATA OF STRING</summary>

 </details>

##

</details>