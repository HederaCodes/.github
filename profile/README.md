# Getting Started

Follow these steps to try HederaCodes:

1. **Clone the repository**
   ```bash
      git clone https://github.com/HederaCodes/backend.git
   ```

2. **Navigate to the backend directory**
   ```bash
   cd backend
   ```

3. **Install dependencies**
   ```bash
   npm install
   ```

4. **Set up your environment variables**
   ```bash
   cp .env.example .env
   ```
   
   Edit the `.env` file and add your Hedera credentials:
   ```
   HEDERA_OPERATOR_ID=0.0.XXXXX
   HEDERA_OPERATOR_KEY=302e...
   ```

5. **Start the development server**
   ```bash
   npm run dev
   ```

6. **Access the application**
   
   Navigate to [https://hedera-codes.vercel.app/](https://hedera-codes.vercel.app/) to see your backend connected to the frontend interface.
