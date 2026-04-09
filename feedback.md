# Feedback — Demo round Day 6

## Nhóm X2 — AI Hỗ trợ xử lý sự cố xe
| Tiêu chí | Điểm (1-5) |
|----------|-----------|
| Problem-solution fit | 4 |
| AI product thinking | 5 |
| Demo quality | 4 |

**Điều làm tốt:** Demo rất tốt và mượt. Nhóm có tư duy sản phẩm (Product thinking) xuất sắc khi vẽ workflow rõ ràng, đặc biệt là việc **trao quyền quyết định cho người dùng (User in the loop)** và có cơ chế double-check (hỏi xác nhận lại) đối với các case nghiêm trọng như xe bị hỏng nặng. 
**Gợi ý cải thiện:** Hiện tại kịch bản đang rất trọn vẹn và an toàn, chưa thấy lỗ hổng lớn nào cần khắc phục ngay. Nhóm có thể nghĩ thêm về cách thu thập feedback sau khi xử lý sự cố để làm giàu RAG.

---

## Nhóm C4 — AI Dự đoán pin
| Tiêu chí | Điểm (1-5) |
|----------|-----------|
| Problem-solution fit | 4 |
| AI product thinking | 3 |
| Demo quality | 4 |

**Điều làm tốt:** Có demo thực tế, xác định được Pain point của người dùng rất rõ ràng và đánh trúng tâm lý lo lắng về pin.
**Gợi ý cải thiện:** Xảy ra tình trạng "Scope creep" — scope sản phẩm vẽ ra quá to nhưng use-cases thực tế lại ít. Việc dự đoán pin hiện tại hơi rập khuôn vì thiếu vắng hoàn toàn các biến số ngoại cảnh thực tế mang tính rủi ro cao (thời tiết, mưa bão, tắc đường, sự cố bất ngờ...). Cần thu hẹp scope và bổ sung biến số để model đáng tin cậy hơn.

---

## Nhóm C5 — AI Cảm biến & Báo cáo cứu hộ
| Tiêu chí | Điểm (1-5) |
|----------|-----------|
| Problem-solution fit | 3 |
| AI product thinking | 2 |
| Demo quality | 4 |

**Điều làm tốt:** Nhóm có chuẩn bị demo sản phẩm để minh họa.
**Gợi ý cải thiện:** Thiếu tư duy về Failure modes (Edge cases vật lý). Nhóm bị "đứng hình" trước câu hỏi thực tế: *Nếu chip cảm biến bị che bởi bùn/lá cây hoặc hỏng do va chạm thì trigger gọi cứu hộ hoạt động thế nào?* Hệ thống hiện tại cũng chưa có cơ chế cover tốt các kịch bản "fail answer" (khi AI nhận diện sai hoặc không phản hồi được). Cần bổ sung fallback flow ngay lập tức.