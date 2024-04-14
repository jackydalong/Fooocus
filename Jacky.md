### colab
https://colab.research.google.com/github/lllyasviel/Fooocus/blob/main/fooocus_colab.ipynb#scrollTo=VjYy0F2gZIPR

!pip install pygit2==1.12.2
%cd /content
!git clone https://github.com/lllyasviel/Fooocus.git
%cd /content/Fooocus
!python entry_with_update.py --share --always-high-vram
