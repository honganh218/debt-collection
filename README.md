# Debt Collection (Báo cáo thu hồi nợ) [PowerBI]
## Introduction
### 1. Introduction to Dataset
- Dataset: OS Collection Performance
- The dataset includes one table containing information on debt collection by partners, organized by month for the years 2020 and 2021
### 2. Data Dictionary
![image](https://github.com/honganh218/debt-collection/assets/133098903/40490f47-f2c5-4225-b9f7-bcd619f37cb3)
### 3. Business Questions
- What are the most effective partners for recovering debt, and what factors contribute to their achievement?
- How can the Head of Finance at Bank X enhance the allocation of the debt portfolio to maximize profits and minimize risk?
- What approaches can the Head of Collection at Bank X adopt to increase debt recovery rates and strengthen collaboration with partners?

## Design Thinking
### Step 1 - Empathize
![image](https://github.com/honganh218/debt-collection/assets/133098903/67ea29b7-2645-48d1-9985-958c4f4f9dee)

### Step 2 - Define
![image](https://github.com/honganh218/debt-collection/assets/133098903/2b0243b9-0d06-4bf4-9f75-e3b1bcc392e4)

### Step 3 - Ideate
![image](https://github.com/honganh218/debt-collection/assets/133098903/9e296e44-532f-4c2f-b66b-4b031be22db5)

### Step 4 - Prototype
![image](https://github.com/honganh218/debt-collection/assets/133098903/94cc0d71-57ad-4253-a3f4-40468cd7aef7)

### Step 5 - Review

## Visualization
![image](https://github.com/honganh218/debt-collection/assets/133098903/b11f29c8-dc3e-44fc-bc66-bd24792672b0)

## Insights and Recommendations
**Overview**:
 - 44% các khoản nợ thuộc nhóm 1080+; 27% thuộc nhóm nợ 720 - 1080 và 22% là nợ xấu
 - SP credit card có tỉ lệ thanh toán cao nhất (0.17%) và overdraft (0.10%)
 - Sản phẩm Secured Loan có tỉ lệ thanh toán thấp nhất (0.02%) và có dư nợ cao thứ 3, trị giá 41T. Cty NDC đứng TOP 1 về việc thu hồi nợ đối với sp này, tỉ lệ thu hồi nợ = 0.03%. Tháng 12/2020 thì sp này được thu hồi nợ tốt nhất, %payment = 0.06%. Tháng 10/2020, cty NDC thu được nhiều khoản thanh toán nợ cho sp này trị giá hơn 950 triệu, tháng 12/2020, cty FBI thu được nhiều khoản thanh toán nợ cho sp này trị giá hơn 1,1 tỷ
 - Sản phẩm Unsecured Loan có dư nợ cao nhất trong các sản phẩm (chiếm gần 50%, trị giá 136T), tỉ lệ thu hồi nợ TB là 0.07%, được thu hồi tốt bởi GLX, HMK và ASA
<br> **TOP 1: Cty NDC**
 - Đứng đầu về balance 45T
 - Tỉ lệ thu hồi nợ TB: 0.09%
 - Từ tháng 10/2020 (0,15%, tăng 0.06% so với tháng 9/2020), cty NDC có sự đột phá về tỉ lệ thanh toán trên tổng dư nợ
 - Kết quả là từ tháng 3 đến tháng 5/2021 cty NDC đã đứng đầu về số tiền thu hồi được, gần 5,5 tỷ (tháng 3/2021)
 - Sản phẩm mà cty này có thể thu hồi nợ tốt là Other (0.32%) và Credit card (0.26%)
 - Có khả năng thu hồi nợ xấu, liên tục đứng TOP thu hồi nợ xấu vào các tháng 10/2020 (gần 1,3 tỉ), 4/2020 (>640tr) và 3/2021 (>370tr)
<br> **TOP 2: Cty ASA**
 - Tỉ lệ thu hồi nợ TB: 0.11%
 - ASA có tỉ lệ thu hồi nợ không ổn định so với cùng kỳ năm trước: 
 + Tháng 1 và 2: Tỉ lệ thu hồi nợ của năm 2021 thấp hơn nhiều so với 2020, cụ thể tháng 1/2020 = 0.2%, 1/2021 = 0.14%; tháng 2/2020 = 0.28%, 2/2021 = 0.06%
 + Tháng 3, 4, 5: Tỉ lệ thu hồi nợ của năm 2021 cao hơn so với 2020, cụ thể tỉ lệ năm 2021/2020 của các tháng 3, 4, 5 lần lượt là 0.17%/0.15% ; 0.12%/0.08% ; 0.11%/0.06%
 + Thế mạnh của cty này là sản phẩm Overdraft, với tỉ lệ thanh toán/dư nợ là 0.26%
<br> **TOP 3: Cty GLX**
 - Tỉ lệ thu hồi nợ TB: 0.11%
 - GLX có tỉ lệ thu hồi nợ của năm 2021 giảm mạnh so với năm 2020
 - SP thế mạnh là Overdraft và HHB
<br> Tỉ lệ thu hồi nợ của năm 2021 của các cty GLX, HNA, DK và AMG có xu hướng tăng so với năm 2020
<br> Cty FBI có tỉ lệ thu hồi nợ TB khá thấp = 0.03%, sản phẩm chủ lực là HHB. Tháng 12/2020 FBI đứng đầu về thu nợ khoản nợ xấu, trị giá hơn 1.2 tỉ
<br> **Recommendation**
 - Phân bổ danh mục nợ theo thế mạnh của từng cty:
 + NDC: Other, Credit Card, Secured Loan
 + ASA: Overdraft, Unsecured Loan
 + GLX: Overdraft, HHB, Unsecured Loan
 + FBI: HHB, Secured Loan
 - Triển khai chính sách ranking: phân bổ portfolio đẹp hơn cho các đối tác có tỷ lệ thu hồi tốt
 

 

 

 

 

 










