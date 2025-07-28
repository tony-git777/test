!apt -y update -qq
!apt -y install -qq aria2 git
!git clone https://github.com/bmaltais/kohya_ss.git
%cd kohya_ss
!pip install -r requirements.txt
