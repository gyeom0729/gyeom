import streamlit as st
import random

# 밈 이미지 URL 리스트
memes = [
    "https://i.imgflip.com/30b1gx.jpg",
    "https://i.imgflip.com/1bij.jpg",
    "https://i.imgflip.com/26am.jpg",
    "https://i.imgflip.com/2/1otk96.jpg",
    "https://i.imgflip.com/3si4.jpg"
]

st.title("랜덤 밈 생성기 🎉")

if st.button("밈 보여줘!"):
    meme_url = random.choice(memes)
    st.image(meme_url, use_column_width=True)
else:
    st.write("버튼을 눌러 랜덤 밈을 확인하세요!")
