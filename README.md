from selenium import webdriver 
from selenium.webdriver.common.by import By 
from selenium.webdriver.common.keys import Keys
from getUser import s9zylz,izemaslan
import time 

class İnstagram():
  def __init__(self,s9zylz,izemaslan):
    self.s9zylz = s9zylz
    self.izemaslan = izemaslan
    self.driver = webdriver.Chrome()

def kullaniciGiris(self):
  self.driver.get("https://www.instagram.com/accounts/login/")
  time.sleep(2)


ınstgram = Instagram (s9zylz,izemaslan)
ınstgram.kullaniciGiris()
