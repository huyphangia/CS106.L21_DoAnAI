# CS106.L21_DoAnAI
Cách chạy:  
python flappybird_AI.py

Để chuyển qua chế độ train agent, mặc định là chế đệ chơi dùng Agent để chơi(False):  
flappybird_AI.py->Config['train'] = true  

Đặt lại max_score, khi vượt qua số điểm này Agent sẽ chơi lại ván mới:  
flappybird_AI.py->Config['max_score'] = ...  

Đặt lại resume_score, khi vượt qua điểm số này sẽ ghi lại 50 trạng thái cuối cùng, từ đó Agent nếu chết sẽ được chơi lại từ 50 trạng thái trước khi chết:    
flappybird_AI.py->Config['resume_score'] = ...  

Khi muốn tắt đồ họa để train nhanh hơn, mặc định là có bật đồ họa(True):  
flappybird_AI.py->Config['showgame'] = false  

Muốn in điểm ra Terminal mỗi khi Agent đạt được a điểm(nên dùng khi train):  
flappybird_AI.py->Config['print_score'] = a   
