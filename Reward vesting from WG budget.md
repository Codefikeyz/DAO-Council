## Reward Vesting from the Working Group Budget  

To begin, visit **Polkadot.js Apps - https://polkadot.js.org/apps/?rpc=wss%3A%2F%2Frpc.joyutils.org#/extrinsics** and connect your wallet extension.  

<img width="958" alt="Screenshot_62" src="https://github.com/user-attachments/assets/efe9f187-cead-4887-a5d2-87d2b0de7b03" />

### Steps to Execute Vesting  

1. **Select Your Account**  
   - This should be the account you used when applying for the lead position.  

2. **Choose the Working Group**  
   - Select the name of the working group from which the budget will be deducted.  

3. **Specify the Operation**  
   - Ensure you select the correct vesting operation for salary allocation.  

4. **Enter the Recipient Account**  
   - This is the account that will receive the vested amount. It can be the same as the account selected in step 1.  

5. **Set the Total Vesting Amount**  
   - Enter the total amount to be locked in vesting, expressed in **HAPI** (not JOY).  
   - To convert JOY to HAPI, follow these steps:  
     - Visit JoyUtils - https://joyutils.org and navigate to **JOY ↔ HAPI Conversion**.  
     - Enter the JOY amount and copy the converted value in HAPI.  
     - Return to **Polkadot.js Apps**, highlight the existing value in **Step 5** (default is **0**), and paste the copied HAPI amount.  
     *(Note: You must highlight a digit before pasting, as empty fields do not support pasting.)*  

   - Example:  
     - 100,000 JOY is converted to its equivalent in HAPI.

  <img width="959" alt="Screenshot_64" src="https://github.com/user-attachments/assets/88ec78ef-8031-43f9-bc47-1f7624a9b456" />

6. **Set the Per-Block Unlock Amount**  
   - Determine how much will be unlocked per block based on your vesting schedule.  
   - Blocks per day: **14,400**  
   - Common vesting durations:  6 months = 2620800 block || 1 year = 5256000 block || 2 years = 10512000 block
     - **6 months (182 days):** `14,400 × 182 = 2,620,800 blocks`  
   - Calculation for per-block unlock:  
     - **Example for 100,000 JOY over 6 months:**  
       - `100,000 ÷ 2,620,800 = 0.0381562882 JOY per block`  
     - Convert **0.0381562882 JOY** to HAPI:  
       - Visit **[JoyUtils](https://joyutils.org)** and input this value.  
       - Copy the result in HAPI (**381562882**) and paste it in the per-block field (following the same pasting instructions as in Step 5).
      
  <img width="960" alt="Screenshot_63" src="https://github.com/user-attachments/assets/1be62356-a578-4494-b6cd-b8c87f5f36d6" />

7. **Set the Start Block**  
   - Find the latest generated block on **Joystream Explorer - https://explorer.joystream.org**.  
   - Copy the latest block number and modify it to a future block number. *(Ensure digits only, no punctuation.)*  
   - Example:  
     - Latest block: **12,095,777**  
     - Future block: **12,095,790** or **12,095,800**  

8. **Include a Rationale**  
   - Click on the **"Include Rationale"** option.  
   - Provide a brief explanation for the transaction. *(You can refer to the example in the screenshot below.)*  

**Submit the Transaction**  
   - Click **"Submit Transaction"** at the bottom right corner.  
   - On the next page, click **"Sign and Submit"** to finalize the process.  

Your reward vesting transaction is now submitted. You can track its status on **[Joystream Explorer](https://explorer.joystream.org)**.  
