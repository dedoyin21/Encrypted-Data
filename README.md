# Quest 1: Pay to unlock a report

Proof of completion of the Fiber interactive tutorial:

1. **Setup:** Both Buyer A–Bottle B and Seller C–Bottle B channels reached `CHANNEL_READY`.

   ![Both channels ready](proofs/quest-1/Setup-channels-ready.png)

2. **Before payment:** Buyer A received the encrypted offer, and attempting to decrypt without the key was rejected.

   ![Encrypted offer on the buyer side](proofs/quest-1/Before-payment-buyer-encrypted-offer.png)

   ![Decryption rejected before payment](proofs/quest-1/Before-payment-decryption-rejected.png)

3. **After payment:** The receipt shows a completed payment of 1 CKB, the payment hash, and a 0.001 CKB routing fee.

   ![Completed payment and payment hash](proofs/quest-1/After-payment-receipt-1ckb-hash.png)

4. **After decryption:** The buyer's decrypted result matches the seller's original sample report.

   ![Seller's original sample report](proofs/quest-1/Seller-encrypt-report.png)

   ![Buyer's decrypted result](proofs/quest-1/After-decryption-buyer-result.png)

The seller's invoice provides additional evidence of the 1 CKB invoice and its payment hash:

![Seller's 1 CKB invoice and payment hash](proofs/quest-1/Seller-invoice-created.png)
