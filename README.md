function setvalue(address,flags,value) local tt={} tt[1]={} tt[1].address=address tt[1].flags=flags tt[1].value=value gg.setValues(tt) end
gg.toast("WELCOME TO FRL MOD GG VIP FOR PUBLIC\n@FRLchannel")
function HOME()
multi = gg.multiChoice({
"Misaki VIP",
"PhantomHive",
"Update Link",
"HS China",
"Magic Bullet",
"GZC Script",
"Clear Third\nParty",
"Headshot Fix Damage",
"FastBullet",
"Headshot\nFeral",
"Aimbot\nFeral",
"WideView\nFeral",
"HS+MB\nChina",
"LessRecoil",
"CrossHair",
"Aimbot 360 \nNot Tested",
"Ultra Damage \nNot Tested",
"WideView \nCari Code Misaki",
"OneClick \nHS+AimBot",
"Lib Based \nAll Hack",
"OneClick \nLessRecoil+Crosshair",

},nil,'Simple Shortcut Script Hehe \nboii')

if multi == nil then else
if multi[1] == true then ch1() end
if multi[2] == true then ch2() end
if multi[3] == true then ch3() end
if multi[4] == true then ch4() end
if multi[5] == true then ch5() end
if multi[6] == true then ch6() end
if multi[7] == true then ch7() end
if multi[8] == true then ch8() end
if multi[9] == true then ch9() end
if multi[10] == true then HEADSHOT() end
if multi[11] == true then AIM() end
if multi[12] == true then ch12() end
if multi[13] == true then ch13() end
if multi[14] == true then RECOIL() end
if multi[15] == true then CROSSHAIR() end
if multi[16] == true then DAMAGE() end
if multi[17] == true then AIM360() end
if multi[18] == true then test() end
if multi[19] == true then oneklik() end
if multi[20] == true then libbased() end
if multi[21] == true then LRC()

end
end
HOMEDM = -1
end

function ch1() ---Misaki Vip
loadfile("/storage/emulated/0/.pubg/trst.lua")()
end

function ch2() ---PhantomHive
V = load(gg.makeRequest("https://pastebin.com/raw/S10QMpsc").content)
pcall(V)
end

function ch3() ---AdminPanel
V = load(gg.makeRequest("https://prvt.000webhostapp.com/Login.php").content)
pcall(V)
end

function ch4()
loadfile("/storage/emulated/0/.pubg/私人的HEADSHOT.lua")()
end

function ch5()
loadfile("/storage/emulated/0/.pubg/Bʀᴜᴛᴀʟ Mᴀɢɪᴄ Bᴜʟʟᴇᴛ.lua")()
end

function ch6()
loadfile("/storage/emulated/0/Notes/GZC script 1.2.lua")()
end

function ch7() ---Clear 3rd
os.remove("src/main/java/com/google/errorprone/annotations")
os.remove("src/main/java/com/google/errorprone/annotations")
os.remove("src/main/java/com/google/errorprone/annotations/concurrent")
os.remove("third_party.java_src.error_prone.project.annotations.Google_internal")
gg.toast("done")
end

function ch8()
loadfile("/storage/emulated/0/.pubg/hs fix damage.lua")()
end

function ch9()
loadfile("/storage/emulated/0/.pubg/Fᴀsᴛ Bᴜʟʟᴇᴛ.lua")()
end

function HEADSHOT() ---Headshot Feral
gg.setRanges(32)
gg.searchNumber("9.20161819458;25;30.5::", 16, false, 536870912, 0, -1)
gg.searchNumber("30.5;25.0:385", 16, false, 536870912, 0, -1)
gg.getResults(50)
gg.editAll("240", 16)
gg.clearResults()
so=gg.getRangesList('libUE4.so')[1].start
py=0x24A74B0
setvalue(so+py,16 , 0)
so=gg.getRangesList('libUE4.so')[1].start
py=0x37c1ba4
setvalue(so+py,16 , 0)
so=gg.getRangesList ("libUE4.so") [1] .start
py = 58465188
setvalue (so + py,16,0)
so=gg.getRangesList ("libUE4.so") [1] .start
py = 0x3B64788
setvalue(so+py,16,50)
so=gg.getRangesList("libUE4.so")[1].start
py = 0x1422EFC 
setvalue(so+py,16,2)
gg.alert("Done")
end

function AIM() ---Aimbot Feral
so=gg.getRangesList('libUE4.so')[1].start 
py=0x258B880 
setvalue(so+py,16,99999)
so=gg.getRangesList("libUE4.so")[1].start
py=38433980 
setvalue(so+py,16,0)
gg.alert("Done")
end

function ch12() ---IpadView
gg.clearResults()
so=gg.getRangesList('libUE4.so')[1].start
py=0x381FCB0
setvalue(so+py,16,265)
gg.alert("Done")
end

function ch13() ---Magic Bullet & Headshot China
loadfile("/storage/emulated/0/.pubg/HEADSHOT-MAGIC.lua")()
gg.alert("Done")
end

function RECOIL() ---Less Recoil
so=gg.getRangesList('libUE4.so')[1].start
py=0x136D4F8
setvalue(so+py,16,0)
so = gg.getRangesList("libUE4.so")[1].start 
py = 0x136BDDC
setvalue(so + py, 4, 0)
gg.alert("Done")
info = gg.prompt({'Add CrossHair?', 'Yes', 'No'}, info, {'checkbox', 'checkbox', 'checkbox'})
if info == nil then os.exit() end
if info[1] then
so=gg.getRangesList('libUE4.so')[1].start
py=0x1C113E8
setvalue(so+py,16,1.40129846e-45)
gg.alert("Done")
end
if info[2] then
os.exit()
end
end

function CROSSHAIR() ---Small Crosshair
so=gg.getRangesList('libUE4.so')[1].start
py=0x1C113E8
setvalue(so+py,16,1.40129846e-45)
gg.alert("Done")
end

function DAMAGE() ---Ultra Damage
so=gg.getRangesList ('libUE4.so') [1] .start
offset=0x147D520 
setvalue(so+offset,16,0.9)
gg.alert(" Ultra Damage Activated ")
end

function AIM360() ---AimBot 360
so=gg.getRangesList('libUE4.so')[1].start
py=0xFB4694
setvalue(so+py,4,0)
gg.alert("AIMBOT SUPER 360° ACTIVED ✓")
end

function test() ---Code IpadView Misaki Cari Sendiri 150 Value.
gg.setRanges(gg.REGION_ANONYMOUS)
---gg.searchNumber("2.80259693e-45;220;25;178;15;100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("220", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(150)
gg.editAll("380", gg.TYPE_FLOAT)
end

function oneklik() ---OneClick AimBot & Headshot
os.remove("src/main/java/com/google/errorprone/annotations")
os.remove("src/main/java/com/google/errorprone/annotations")
os.remove("src/main/java/com/google/errorprone/annotations/concurrent")
os.remove("third_party.java_src.error_prone.project.annotations.Google_internal")
gg.toast("done")
loadfile("/storage/emulated/0/.pubg/HEADSHOT-MAGIC.lua")()
so=gg.getRangesList('libUE4.so')[1].start 
py=0x258B880 
setvalue(so+py,16,99999)
so=gg.getRangesList("libUE4.so")[1].start
py=38433980 
setvalue(so+py,16,0)
gg.alert("Done")
end

function libbased() ---Lib Based
os.remove("src/main/java/com/google/errorprone/annotations")
os.remove("src/main/java/com/google/errorprone/annotations")
os.remove("src/main/java/com/google/errorprone/annotations/concurrent")
os.remove("third_party.java_src.error_prone.project.annotations.Google_internal")
gg.toast("done")
loadfile("/storage/emulated/0/.pubg/PUBG UNKNOWN 1.2.0.lua")()
end


function LRC() --- OneClick LessRecoil+Small Crosshair
os.remove("src/main/java/com/google/errorprone/annotations")
os.remove("src/main/java/com/google/errorprone/annotations")
os.remove("src/main/java/com/google/errorprone/annotations/concurrent")
os.remove("third_party.java_src.error_prone.project.annotations.Google_internal")
gg.toast("done")
so=gg.getRangesList('libUE4.so')[1].start
py=0x1C113E8
setvalue(so+py,16,1.40129846e-45)
so=gg.getRangesList('libUE4.so')[1].start
py=0x136D4F8
setvalue(so+py,16,0)
so = gg.getRangesList("libUE4.so")[1].start 
py = 0x136BDDC
setvalue(so + py, 4, 0)
gg.alert("Done")
end

while true do 
  if gg.isVisible(false) then 
   HOMEDM = 1
    gg.setVisible(false) 
  end 
  if HOMEDM == 1 then HOME() end 
 end


---so=gg.getRangesList('libUE4.so')[1].start
---py=0x3C491D0
---setvalue(so+py,16,40.0)


---gg.clearResults()
---so=gg.getRangesList('libUE4.so')[1].start
---py=0x381FCB0
---setvalue(so+py,16,265)
---gg.clearResults()
---gg.toast("iPad View Activated")


---function setvalue(address,flags,value) local tt={} tt[1]={} tt[1].address=address tt[1].flags=flags tt[1].value=value gg.setValues(tt) end
---so=gg.getRangesList ('libUE4.so') [1] .start
---offset=0x147D520 
---setvalue(so+offset,16,0.9)
---gg.alert(" Ultra Damage Activated ")

---function AB()
---so=gg.getRangesList('libUE4.so')[1].start
---py=0xFB4694
---setvalue(so+py,4,0)
---gg.toast("AIMBOT SUPER 360° ACTIVED ✓")
