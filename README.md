# Changing_voice
Chương trình chuyển dổi giọng ca sĩ yêu thích sang 1 bài hát khác.
Chương trình sử dụng các model sau: epsnet opencpop + Bigvgan để dự đoán và tạo wav, so-vits-svc dùng để chuyển đổi giọng của ca sĩ yêu thích thay cho giọng của ca sĩ gốc. Do dataset của opencpop là wav không nhạc nên dùng thêm Musicgen để tạo thêm giai điệu phù hợp với tempo của wav đã tạo
