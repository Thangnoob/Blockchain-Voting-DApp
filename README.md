# Blockchain Voting DApp

Một ứng dụng bỏ phiếu phi tập trung (Voting DApp) viết bằng Solidity và triển khai trên testnet **Soliphia**.  
Cho phép người dùng bỏ phiếu cho các đề xuất và xem kết quả trực tiếp trên blockchain.

## 🛠 Công nghệ sử dụng
- **Solidity** (Smart Contract)
- **Remix IDE** (Viết & deploy hợp đồng)
- **MetaMask** (Kết nối ví, ký giao dịch)
- **Soliphia Testnet**

## 🚀 Cách chạy

### 1. Chuẩn bị
- Cài [MetaMask](https://metamask.io/)
- Chuyển sang mạng **Soliphia Testnet**
- Nhận token test từ faucet của Soliphia

### 2. Deploy Smart Contract
1. Mở [Remix IDE](https://remix.ethereum.org/)
2. Tạo file `Voting.sol` và code smart contract
3. Compile với Solidity 0.8.x
4. Deploy với tham số mảng tên đề xuất, ví dụ:
["Alice", "Bob", "Charlie"]
5. Xác nhận giao dịch trên MetaMask

### 3. Test Voting
- Gọi hàm `vote(proposalIndex)` để bỏ phiếu
- Gọi `getProposals()` để xem kết quả

