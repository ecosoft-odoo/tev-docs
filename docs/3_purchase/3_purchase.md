# กระบวนการจัดซื้อจัดจ้าง

## การสร้างใบสั่งซื้อสั่งจ้าง (Purchase Order:PO)

**Menu:** Purchase > Orders > Purchase Requests

1. ค้นหารายการ Purchase Request (PR) เพื่อสร้าง Requests for Quotation (RFQ)
      1. เอกสาร PR อยู่ในสถานะที่ได้รับการอนุมัติแล้ว (Approved)
      2. คลิกที่ปุ่ม Create RFQ เพื่อสร้างเอกสาร RFQ
      3. เลือก Vendor ที่ต้องการจัดซื้อจัดจ้าง ตรวจสอบ Product และ Quantity และกดปุ่ม Create
      4. ระบบจะพาไปยังเอกสาร RFQ ที่ถูกสร้างขึ้นใหม่ ให้คลิกเพื่อเปิดเอกสาร

    ![](pix/1_pr_new.png)

2. ตรวจสอบความถูกต้อง และยืนยันเอกสาร Requests for Quotation (RFQ)
      1. Currency: กรณีเป็นการจัดซื้อจัดจ้างต่างประเทศ เปลี่ยน Currency เป็นสกุลเงินที่ต้องการ
      2. Order Deadline: วันที่การสั่งซื้อสั่งจ้าง
      3. Receipt Date: วันที่ส่งมอบสินค้า/บริการที่ตกลงกับ Vendor
      4. Quantity: จำนวนขอซื้อ
      5. Unit Price: ราคาต่อ 1 หน่วย
      6. กดปุ่ม Confirm เพื่อยืนยันเอกสาร
    เมื่อสร้างเอกสารเสร็จแล้วให้กด Save เพื่อบันทึกข้อมูล

      ![](pix/te_confirm.png)

3. ส่งเอกสาร RFQ เข้ากระบวนการอนุมัติจัดซื้อจัดจ้าง
      1. สำหรับ RFQ ที่เลือก ให้กดปุ่ม Request Validation
      ![](pix/rfq_tier_request_validation.png)
      2. เอกสารนี้จะเข้ากระบวนการอนุมัติ ซึ่งตารางการอนุมัติจะแสดงอยู่ที่ด้านล่างของเอกสาร
      ![](pix/rfq_tier_validation.png)

    !!! Info
        * ลำดับขั้นการอนุมัติในระบบ เป็นดังนี้
                * วงเงิน ไม่เกิน 100,000 :: Purchase Manager และ Director Purchase
                * วงเงิน มากกว่า 100,000 :: Purchase Manager และ K.Kittikorn Phinitwongwitthaya

    !!! Note
        เอกสาร RFQ ที่ส่งเข้ารับการอนุมัติ ในภายหลังเมื่อได้รับการอนุมัติแล้ว เอกสารจะเปลี่ยนสถานะเป็น Purchase Order (PO)
            
            ![](pix/rfp_approved.png)
            
End.
