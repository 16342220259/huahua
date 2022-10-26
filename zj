gg.setVisible(false)
local sz='http://cloud.tonwzf.xyz/api/v3/file/get/2472/%E5%9F%BA%E6%9C%AC%E6%95%B0%E7%BB%84.lua?sign=qYyCuY860VFCbAhKRwePGqZZbMc9bx0AnTgj6osJ1yw%3D%3A0'
pcall(load(gg.makeRequest(sz).content))--基本数组

local yd='http://cloud.tonwzf.xyz/api/v3/file/get/2471/%E5%8E%9F%E5%9C%B0%E6%95%B0%E7%BB%84.lua?sign=eY72tI9gTuMvEnqOHE9GBZD8I25-tym16PDap3GhRCE%3D%3A0'
pcall(load(gg.makeRequest(yd).content))--原地数组




function addrjump(a,b) tem=gg.getValues({[1]={address=a+b,flags=32}})[1].value return tem end

function doAction(method) load(method .. "()")() end

function jkmmchoice(cd,name) tmp={}  for k,v in pairs(cd) do  tmp[#tmp + 1] = {}  tmp[#tmp] = cd[k][1]  end  SN=gg.choice(tmp,{},name) if SN then doAction(cd[SN][2]) end end

gg.clearList() --清空保存
gg.clearResults() 
gg.setRanges(8) --设置内存范围
gg.searchNumber("15000",16) --搜索数字
result = gg.getResults(1) --获取当前内存范围
fanwei = result[1].address 
gg.clearResults()--清除搜索

function search(...) local sousuo1 = {...} gg.searchNumber(sousuo1[1],sousuo1[2],false, gg.SIGN_EQUAL,0x1000000000,fanwei) end

function searchaddr(nclx,sj,lx,py1,pylx,pysj,py2,name) gg.clearResults()  gg.setRanges(nclx)   if nclx == 4 then--内存类型xa什么的 
  gg.setRanges(4|-2080896)  search(sj,lx)  else  gg.searchNumber(sj,lx) end  local tmp = {}  for k, v in ipairs(gg.getResults(gg.getResultCount())) do tmp[k] = { address = v.address + py1, flags = pylx } end 
       for k, v in ipairs(gg.getValues(tmp)) do  if v.value == pysj then  gg.toast(name.."成功✓️")   return v.address+py2   end   end   gg.toast(name.."️失败") end

local init_tabkey={"address","flags","value","freeze"} 
function seaio(t,a,b,c,d) t[#t+1]={}  t[#t][init_tabkey[1]]=a  t[#t][init_tabkey[2]]=b if c then t[#t][init_tabkey[3]]=c end  if d then t[#t][init_tabkey[4]]=d   end end

--测好友升高
function mumuxfa(a,b,c)
tem=gg.getValues({[1]={address=a+b,flags=32}})[1].value
return tem + c end
Shengdz = function() return mumuxfa(mumuxfa(rwdz,0x123CB4,0),0,0) end--好友升高配置
function xhdz(q,w,e,r,t,y)tmp={} for i=1,q do tmp[i]={address=w+i*e,flags=r,value=t,freeze=y} end gg.setValues(tmp) gg.addListItems(tmp) end --窥屏配置

function forseaio(i,j,t,a,py,xhpy,b,c,d) 
--i j 循环 t数组 a py xhpy =a b = b c = c  d= d
for k=i,j do seaio(t,a+py+xhpy*k,b,c,d) end 
end--这个真的很好用别问我为什么

function YUS()
	QWORD=gg.TYPE_QWORD			--32
	FLOAT=gg.TYPE_FLOAT			--16
	DWORD=gg.TYPE_DWORD			--4
	X = nil 			       --当前地图索引
	LZTIME = 4000				--蜡烛瞬移
	CandleSleepTime = LZTIME	       --蜡烛瞬移
	GTtime = 10000		       --蜡烛过图
	JRtime=60000		   	       --金人瞬移时间
	GTTIME=10000			       --过图时间金人
-------指针	

-----人物指针
function rwhx()
gg.setVisible(false)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_CODE_APP)
gg.searchNumber("-1067909120;3;3507Q;1065353216:500", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
gg.refineNumber("3507", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
rwcs=gg.getResults(1) 
    rwcs1=rwcs[1].address+4
end
rwhx()
rwdz=rwcs1

--------指针
so=gg.getRangesList('libBootloader.so')[1].start
gg.addListItems({{address=gg.getRangesList('libBootloader.so')[1].start,flags=32,name='so'}})


local pyy='http://cloud.tonwzf.xyz/api/v3/file/get/2643/%E8%87%AA%E7%94%A8%E5%81%8F%E7%A7%BB%E6%95%B0%E7%BB%84.lua?sign=Qe-YOpxjSLzgjF9H7AXHceDd5EKRS7m8IRqzWN3YH8E%3D%3A0'
pcall(load(gg.makeRequest(pyy).content))
-------------------------
  candle={}--点蜡烛
  forseaio(1,550,candle,dianhuo,"-448","448",16,1)

  zhpy = {}----炸花
  forseaio(1,266,zhpy,Azhahua,"-8","8",16,0)

  xianlazhu = {}----隐藏蜡烛
  forseaio(1,193,xianlazhu,yclzaddr,"-112","112",4)
  
  rwzb = {}----坐标
  forseaio(1,3,rwzb,rwdz,"0","4",16)
  
  wxnladdr = {}----无限能量
  seaio(wxnladdr,nengliang,16,14)

  dqwzaddr = {}--地图判断
seaio(dqwzaddr,dtaddr,4)
  
  diaoxiang= {}----献祭献祭雕像
  forseaio(1,63,diaoxiang,xjdiaoxiang,"0","0",4,2)
 
  LightCount = {}----光翼
  seaio(LightCount,dengjiaddr,4)

  LightChild = {}--吸光翼
  forseaio(1,12,LightChild,guangyiaddr,"-304",304,4)
  
  Lightboom = {}--炸翼
seaio(Lightboom,zhayi,4)

  lzyxaddr = {}--无限影像
  seaio(lzyxaddr,luzhiyx,4)
end

--底层功能--
function TP(nt, xyz)
  tmp = {}
  for i = 1, 3 do
    seaio(tmp,nt + i * 4,16,xyz[i])
  end
  gg.setValues(tmp)
end

function Teleport(xzy)
  TP(rwdz,xzy)
end

function xxtp(sy)   --线性跑图
    local xzy=A_Get_zero()
    local tmp={}
    local juli=0
    for i=1,3 do
        tmp[i]=sy[i]-xzy[i]
        juli=juli+(tmp[i])^2--烛火距离
    end
    local cisu=math.ceil(math.sqrt(juli)/xxsd)--瞬移次数
    for i=1,3 do
        tmp[i]=tmp[i]/cisu--每个轴的一次的瞬移距离
    end
    
    for i=1,cisu do
        tmp1={}
        for j=1,3 do
            seaio(tmp1,rwdz+4*j,16,(xzy[j]+i*tmp[j]),true)
        end
        gg.addListItems(tmp1)
        --gg.sleep(10)
    end
    gg.removeListItems(tmp1)
end
xxsd=0.1

function xxtpset()--线性跑图设置
local menu = gg.prompt({
    "线性瞬移每秒移动距离(单位-秒)[1;100]"
  },
   {
   20
   },
   {"number",
   })
    if not menu then return 0 end
   xxsd=((menu[1]..".0")/100)
end
--游戏变速
function jiasu(x)
  tmp={}
  seaio(tmp,jiasuaddr,16,x,true)
  gg.setValues(tmp)
  gg.addListItems(tmp)
end

function A_jlz()--判断蜡烛
  if #HandCandle ~= 0 then
    gg.setValues(HandCandle)
  end
 end

--获取人物位置
function A_Get_zero(flag)
  flag = flag or 0
  local xzy = gg.getValues(rwzb)
  for i = 1, 3 do
    xzy[i] = xzy[i].value
  end
  if flag ~= 0 then
    gg.copyText("{" .. xzy[1] .. ", " .. xzy[2] .. ", " .. xzy[3] .. "}", false)
    gg.toast("{" .. xzy[1] .. ", " .. xzy[2] .. ", " .. xzy[3] .. "}")
  end
  return xzy
end
--结束xyz

--房间人数
 function A_fjrs()
  rs = {}
  for i=1,1 do
    rs[i] = {address = fjrs,flags = 4}
    rs = gg.getValues(rs)
    rs[i] = rs[i].value
  end
end

--房间刷新
function fjsx()
sxsx={}
seaio(sxsx,sxdz,4,0)
sxsx[1].freeze=true
gg.addListItems(sxsx)
gg.sleep(3000)
sxsx[1].freeze=false
gg.addListItems(sxsx)
end

function xianlazhuk()--显蜡烛
  for i = 1,193 do
    xianlazhu[i].value = 28673
  end
  gg.setValues(xianlazhu)
  gg.toast("已显示隐藏蜡烛")
end

--吸花
function xihua()
  for i=1,256 do
    TP(i*944+huazb, A_Get_zero())
  end
end

function getFlowerAddress(M)--炸花
  if M==1 then
    for j = 1, 266 do
      zhpy[j].freeze = false
    end
    gg.setValues(zhpy)
    gg.removeListItems(zhpy)
   else
    for j = 1, 266 do
      zhpy[j].freeze = true
    end
    gg.setValues(zhpy)
    gg.addListItems(zhpy)
  end
end
--位置判断
function wzpd()
  weizhi = gg.getValues(dqwzaddr)
  for i = 1 , #map do
    if weizhi[1].value == map[i][2] then
      X = i
      return i
    end
  end
end

--修改角色状态（站0 一级坐2 二级坐1 躺3）
function suozishi(status)
    local action = {
        {flags = DWORD, value = status, address = zspy}
    }
    gg.setValues(action)
end
--结束

-- 全图点火
function LightAFire()
  gg.setValues(candle)
  getFlowerAddress(1)
  gg.sleep(200)
  getFlowerAddress()
end

function absorbCandlelight()--吸烛火
  xihua()
  gg.sleep(200)
  LightAFire()
  gg.clearResults()
  gg.setRanges(4|-2080896)
  search("-842203136", 4)
  local resultCount = gg.getResultCount()
  if resultCount == 0 then
    gg.toast("吸收蜡烛地址获取失败")
    os.exit()
  end
  local result = gg.getResults(resultCount)
  local tmp = {}
  for i, v in ipairs(result) do
    seaio(tmp,v.address - 12,16)
  end
  local x = {}
  tmp = gg.getValues(tmp)
  for i, v in ipairs(tmp) do
    if "" .. v.value == "3.5" then
      seaio(x,tmp[i].address,16,999999)
    end
  end
  jiasu(15)
  gg.setValues(x)
  gg.toast("吸收"..(#x).."点烛火")
  gg.sleep(350)
  jiasu(1)
  gg.clearResults()
end

function A_LightChip()--吸光标
  local LightChip = {}
  local xzy = A_Get_zero()
  for i = 1, 128 do
    for a = 1, 3 do
      LightChip[#LightChip + 1] = {
        address = LightChipAddr + 528 * (i - 1) + 4 * (a - 1),
        flags = FLOAT,
        value = xzy[a]
      }
    end
  end
  jiasu(15)
  gg.setValues(LightChip)
  gg.sleep(1000)
  jiasu(1)
end

--一键手跑
function yijian()
--xianlazhuk() ---显蜡烛
LightAFire()---全图点火
absorbCandlelight()--吸火
end

function jkptyj()
xianlazhuk() ---显蜡烛
LightAFire()---全图点火
absorbCandlelight()--吸火
end

function renyimen(str)--任意门
bto={"Black"}
  map_color=bto[math.random(1,#bto)]
  local dat,offset,date,door,doorx,zb,tem,temb,color  
  door,doorx=csaddr,{map[str][1]:byte(0,-1)}
  color={(string.char(#map_color*2)..map_color):byte(0,-1)}
  tem,temb={},{}
seaio(tem,door-0x14,16,80000)
    seaio(tem,door-0x28,16,80000)
    seaio(tem,door-0x3C,16,80000)
    seaio(temb,door+0x60,4,1)
    seaio(temb,door+0x2C,32,49)
    seaio(temb,door+0x2C+8,32,24)
    seaio(temb,door+0x2C+16,32,door+0x3348)
    seaio(temb,door+0x3394,4,1)
  for j=1,16 do seaio(temb,door+0x2C+24+j-1,1,color[j] or 0) end
  for j=1,24 do seaio(temb,door+0x3348+j-1,1,doorx[j] or 0) end
  gg.setValues(temb)
  gg.setValues(tem)
  renyimentime = os.time()
  X=nil
  while (X ~= str) do
    wzpd()
    renyimentime1 = os.time() - renyimentime
    if renyimentime1 > 11 then gg.toast("传送超时") return end
  end
  gg.toast("已到达【"..map[str][3].."】")
  end
 
  function wsp()
  wzpd()
  if io.open(lj..map[X][3],"r")==nil then
    gg.toast("没有该图数据")
   --   local Dtlzz=map[X][3]=gg.getValues({[1]={address=map[X][3],flags=4}})[1].value
   -- GL(Dtlzz,4,Dtlzz,false)
 --   print("地图录制"，Dtlz)
    bai(1)
  else
    bai(2)
  end
end

-- 智能找门
function IntelligentFindDoor()
  wzpd()
  for i = 1,#tempMap do
    if X==tempMap[i][1] then
      tmp={} 
	  for j = 1,#tempMap[i][3] do
	  tmp[#tmp + 1] = {} 
	  tmp[#tmp] = map[tempMap[i][3][j]][3] 
	  end
      table.insert(tmp, "返回主页")
      menu = gg.choice(tmp, {})
      if menu==#tmp then
        RunModeBigOrSmallMenu()
        return 0
       elseif menu then
        Teleport(tempMap[i][2][menu])
        return 0
      end
    end
  end
  gg.toast("当前地图未录入")
  gg.sleep(1000)
  RunModeBigOrSmallMenu()
end

function csjc(x,j)--传送检测
  local tmp=0
  while true do
    Teleport(x)
    gg.sleep(8000)
    wzpd()
    tmp=tmp+1
    if tmp==3 then gg.toast("传送超时正在利用传送门重传" ) qt(j) end
    if X == j then
      gg.toast("当前地图为"..map[X][3])
      gg.sleep(2000)
      break
    end
    gg.sleep(2000)
    gg.toast("位置不对正在重传")
  end
end

function qt(x)
  wzpd()
  if X ~= x then
    jiasu(20)
    renyimen(x)
    gg.sleep(300)
    jiasu(10)
    jiasu(5)
    jiasu(1)
  end
  jiasu(1)
end

--任意传送开始
function M_rycs()
  FX = "M_rycs"
  local menu = gg.choice({
    "遇境",
    "晨岛",
    "云野",
    "雨林",
    "霞谷",
    "暮土",
    "禁阁",
    "暴风眼",
    "王子季",
    "其他",
    "返回主页"
  }, {})
  if menu == 1 then
    qt(menu)
  elseif menu ~= nil and menu < 12 then
local id={
{1},
{2,41,42,43,44,45},--晨岛
{3,4,5,6,7,8,40},--云野
{9,10,11,12,13,14,49,56},--雨林
{15,16,17,18,19,20,46,47,48,60,61},--峡谷
{21,22,23,24,25,26,27,55,59},--墓土
{28,29,30,31,32,57},--禁阁
{33,34,35,36,37,38,39},--暴风
{50,51,52,53,54,58},--王子
{62,63,64,65,66,67,68},--其他
}
  tmp={}
  for i = 1,#id[menu] do--菜单生成
  tmp[#tmp + 1] = {}
  tmp[#tmp] = map[id[menu][i]][3]
  end
  menu2 = gg.choice(tmp,{})
  if menu2~=nil then qt(id[menu][menu2]) end
  else
  Main()
  end
  end
--跑图模块



luzkg="未开启"
function luzhilazhu()
if luzkg == "未开启" then
lutab={}
seaio(lutab,lzyxaddr,4,1,true)
gg.addListItems(lutab)
luzkg="已开启"
gg.toast("录制蜡烛已开启")
else
lutap={}
seaio(lutap,lzyxaddr,4,0,true)
gg.addListItems(lutap)
gg.removeListItems(lutap)
luzkg="未开启"
gg.toast("录制蜡烛已关闭")
  end
end

function cshjb()--初始化脚本
cshjb1=gg.alert("游戏卡顿,手机发热可初始化脚本。功能开的太多也会造成游戏卡顿望悉知。是否初始化脚本？","是","否")
if cshjb1==1 then
gg.clearList()
gg.clearResults() else
Main() end
end

function PTSZ()--跑图设置
  bin=gg.prompt({"蜡烛瞬移间隔(单位：毫秒)","大图过图时间(单位：毫秒)"},
  {LZTIME,GTtime},
  {'number','number'})
  if bin~= nil then
    LZTIME=bin[1]
    GTtime=bin[2]
    CandleSleepTime = LZTIME
    gg.toast("蜡烛间隔："..LZTIME.."ms 过图间隔："..GTtime.."ms ")
  end
end

function PTSmall(ptmap,pd)
  wzpd()
  if pd == 17 then
    LightAFire()
    for i = 10, 20 do
      if (i == 11) then
        suozishi(2)
        CandleSleepTime = 15000
        suozishi(2)
        gg.toast("坐下开个门")
        suozishi(2)
        jiasu(5)
       elseif ( i == 13) then
        CandleSleepTime = LZTIME
        A_LightChip()
        absorbCandlelight()
       elseif (i == 15) then
        CandleSleepTime = 10000
       elseif (i == 16) then
        gg.sleep(3000)
        jiasu(5)
        Teleport({58.34699630737305;138.28443908691406;-218.4073944091797})
        gg.sleep(2000)
        for i=1,7 do
          gg.sleep(2000)
          jiasu(5)
          A_LightChip()
        end
        LightAFire()
        CandleSleepTime = 40000
        gg.toast("准备拿蜡烛")
        jiasu(5)
       else
        CandleSleepTime = LZTIME
      end
      Teleport(map16[i])
      gg.toast("瞬移 [飞行赛道] 蜡烛 [" .. i .. "] 完成")
      gg.sleep(CandleSleepTime)
    end
    absorbCandlelight()
    gg.toast("[飞行赛道] 结束")
   else
   --主跑图
    if pd~=X then gg.toast("请在("..map[pd][3]..")开启") return end
    LightAFire()
    for i = 1, #ptmap do
      Teleport(ptmap[i])
      gg.toast("瞬移"..map[pd][3].."蜡烛 [" .. i .. "] 完成")
      gg.sleep(CandleSleepTime)
    end
    absorbCandlelight()
    gg.sleep(1000)
    gg.toast(""..map[pd][3].."结束")
  end
end

function PTsleep(time)
  local T=time/100
  local i=0
  while true do
    gg.sleep(100)
    i=i+1
    gg.toast("过图时间剩余:"..((T-i)/10).."."..((T-i)%10).."s")
    if i==T then
      break
    end
  end
end
--跑图模块结束--

-------------------------------常用菜单-------------------------------
function xghz()--修改画质
jk=gg.prompt({"帧率[1;3]","画质[1;300]"},{"2","120"},
           {"number","number"})
if jk==nil then return end
  gg.setRanges(1)
  gg.addListItems({[1]={address=zldz,flags=4,freeze = true,value=jk[1]}})
  gg.addListItems({[1]={address=hzdz,flags=4,freeze = true,value=jk[2]}})
gg.clearList()
gg.alert("开启成功,切换画质后生效")
end

function qhty()--强化跳跃
bgg=gg.prompt({"设置加强倍数[1;30]"},{"1"},{"number"})
if bgg==nil then return 0 end
gg.clearResults()
gg.setRanges(8)
gg.searchNumber('-1D;1F;1D::25',gg.TYPE_FLOAT)
gg.refineNumber('1',gg.TYPE_FLOAT)
gg.getResults(1)
gg.editAll(bgg[1],gg.TYPE_FLOAT, false, gg.SING_EQUAL, 0, -1)
gg.clearResults()
end

function hqqsgn()--获取潜水功能
qt(58)
gg.sleep(8000)
Teleport({144.69009399414062;0.6873548626899719;-12.090353965759277})
gg.sleep(1000)
miaozuotan()
gg.sleep(100)
jiasu(10)
gg.sleep(11000)
jiasu(1)
end

function qcfq()   ----去除风墙
    FQaddr = searchaddr(4, 303251, 4, 0x10, 4, 2, "0x88", "风墙")
   
    if not FQaddr then
        return
    end
    local base = FQaddr
    local con, t = {}
    while true do
        base = base + "0x100"
        t = gg.getValues({ { address = base, flags = 16 } })[1].value
        if (t == "0.0") then
            break
        end
        seaio(con, base - 0x1C, 16, 0)
    end
    gg.setValues(con)
end

wxnlkg="-〘 ❌ 〙"    --无限能量
function UnlimitedEnergyStatus(status)
  if status or wxnlkg=="-〘 ✅ 〙" then
    gg.toast("无限能量,已关闭")    
    wxnlkg="-〘 ❌ 〙"    
    wxnladdr[1].freeze = false    
   else   
    gg.toast("无限能量,已开启")    
    wxnlkg="-〘 ✅ 〙"    
    wxnladdr[1].freeze = true    
  end  
  gg.addListItems(wxnladdr)  
end

home="-〘 ✅ 〙"    --快速回家
 
function Fasthome()--白耳机
--gg.setConfig(2131427463,102)--对游戏隐藏23
if home=="-〘 ❌ 〙" then
gg.setValues({{address=fasthome,flags=4,value=-721215457}}) 
home="-〘 ✅ 〙" 
else
gg.setValues({{address=fasthome,flags=4,value=1409289387}}) 
home="-〘 ❌ 〙" 
--gg.setConfig(2131427463,110)--对游戏隐藏234
end
end

 
wxyqkg="-〘 ❌ 〙"    --无限氧气
function yangqi()
if wxyqkg=="-〘 ❌ 〙" then
gg.toast("无限氧气已开启")
wxyqtab={}
seaio(wxyqtab,wxyq,16,14,true)
gg.addListItems(wxyqtab)
wxyqkg="-〘 ✅ 〙"
else
gg.toast("无限氧气已关闭")
wxyqtap={}
seaio(wxyqtap,wxyq,16,14,true)
gg.addListItems(wxyqtap)
gg.removeListItems(wxyqtap)
wxyqkg="-〘 ❌ 〙"
  end
end

function lsdz()--临时动作
    local xz = {}
    for i = 1, #xianzu do
    seaio(xz,yjxzaddra+(i-1)*0x30,4,xianzu[i][1],true)
    end
    seaio(xz, yjxzaddrb, 4, 99, true)
    gg.addListItems(xz)
    
    
end

kpkg="-〘 ❌ 〙"
function ltkp()--聊天窥屏
ltpd=searchaddr(4,"65540",4,"0x18",4,"32","8","")
if not ltpd then end
local tmp={}
seaio(tmp,ltpd,4,15,true)
for i = 1,32 do
    seaio(tmp,ltpd-0x3190-(i-1)*0x21C,4,15,true)
end
    if kpkg=="-〘 ❌ 〙" then
        gg.addListItems(tmp)
        kpkg="-〘 ✅ 〙"
    else
        gg.removeListItems(tmp)
        gg.clearResults()
        gg.clearList()
        kpkg="-〘 ❌ 〙"
    end
end

HB="-〘 ❌ 〙" 
function ltkp1()--新聊天窥屏
--gg.setConfig(2131427463,102)--游戏隐藏23
if HB == "-〘 ❌ 〙" then
gg.setValues({{address=ltkb2,flags=4,value=505729024}})
gg.setValues({{address=ltkb3,flags=4,value=1384120320}})
HB="-〘 ✅ 〙" 
else
gg.setValues({{address=ltkb2,flags=4,value=506030080}})
gg.setValues({{address=ltkb3,flags=4,value=-251657601}})
 HB="-〘 ❌ 〙" --gg.setConfig(2131427463, 14)--游戏隐藏234
 end 
 end

function yxbs()--游戏变速
  local speed = gg.prompt({
    "请输入变速倍数(输入0世界将静止)"
  }, {
    [1] = "1"
  }, {
    [1] = "number"
  })
  if speed == nil or speed[1]=="" then 
  return 0 
  else speed = tonumber(speed[1]) 
  end 
  jiasu(speed)
end

function byjr()--拨云见日
gg.alert("顾名思义,我想傻子也懂在有云的地图开启。")
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("16",16)
gg.getResults(gg.getResultsCount())
gg.editAll("-15",16)
gg.clearResults()
end

function hdzh()----活动召回
  gg.clearResults()
  gg.setRanges(4|-2080896)
  search(":global_",1)
  gg.getResults(9999)
  gg.editAll(":00",1)
  gg.clearResults()
  end

function yjfk()--一键复刻
gg.toast("正在检测本周复刻先祖…")
gg.sleep(2000)
yjfkpd=gg.alert("本周复刻先祖是:粗辫子先祖，是否自动先祖？","是","否")
if yjfkpd==1 then
qt(23)
gg.sleep(6000)
Teleport({279.0246276855469;103.86029052734375;350.5441589355469})
gg.sleep(1000)
LightAFire()
gg.sleep(1000)
for i=1,8 do
gg.sleep(3000)
A_LightChip()
end
Teleport({283.9629821777344;121.72711181640625;352.1094970703125})
gg.alert("复刻成功,点亮先祖即可") end
if yjfkpd==2 then Main() end
end

----封装魔法商店
function GL(address,flags,value,freeze)
t={}
t[1]={}
t[1].address=address
t[1].flags=flags
t[1].value=value
t[1].freeze=freeze
gg.setValues(t)
gg.addListItems(t)
end
---魔法商店
function mfsd()
local mfcd=gg.choice({"免费魔法","道具魔法","活动商店","体型魔法"},{},"不用再去方舟领魔法啦!")
if mfcd==nil then cy() return 0 end
if mfcd==1 then mfsdk(mfcd) end
if mfcd==2 then mfsdk(3) end
end

function mfsdk(x)
sdwb={',SpellShop_Oasis_Potion',',SpellShop_Oasis_Scroll','(SpellShop_Love_Spell','*SpellShop_Oasis_Spell'}
yp={}
GL(mfkg,4,1)
GL(mfkg+0x48,4,256,true)
for i=1,24 do
yp[i]={address=mfkg+0x27+i,value=string.byte(sdwb[x],i,i) or 0
,flags=1}
end
gg.setValues(yp) 
gg.alert("开启成功，请点击?领取")
end
function anniuinit()
gg.alert([[
游戏内各种按钮呼出
再点击一次即可关闭
部分按钮点了会闪退
重启游戏就好了
源码来自kk
]])
local niuaddr=searchaddr(4,"28,595",4,0x44,4,1,"-0x24","按钮")
--dz(32,niuaddr,"按钮")
local tmp={}
seaio(tmp,niuaddr-8,32)
local ss=gg.getValues(tmp)[1].value
gg.clearResults()
gg.setRanges(4|-2080896)
gg.searchNumber(ss, 32,false, gg.SIGN_EQUAL,niuaddr-0x1FFFF,niuaddr+0x1FFFF)
local ResultCount = gg.getResultCount()
anniucd={}--菜单
anaddr={}
if ResultCount ~= 0 then
for k, v in ipairs(gg.getResults(ResultCount)) do
anaddr[k]=v.address+8
anniucd[k]=k..".*⸜( •ᴗ• )⸝*"
end
anniucd[#anniucd+1]="退出"
end
end
function anniu()
FX="anniu"
if not anniucd then anniuinit() end
SN=gg.choice(anniucd,nil,"获取"..(#anniucd-1).."个按钮\n1.部分按钮触发可能会导致闪退\n2.再次点击可关闭")
if not SN or SN==#anniucd then
return 0
else
tmp={}
seaio(tmp,anaddr[SN],4,1)
local pd=gg.getValues(tmp)[1].value
if pd~=0 then 
tmp={}
seaio(tmp,anaddr[SN],4,0)
else
tmp={}
seaio(tmp,anaddr[SN],4,1)
end
gg.setValues(tmp)
gg.addListItems(tmp)
end
end
function zhafang()
gg.alert("点击悬浮窗结束 10秒左右有效果")
tmp={}
seaio(tmp,zf,16,41249,true)
gg.addListItems(tmp)
while true do
if gg.isVisible(true) then
gg.setVisible(false)
gg.clearList()
gg.clearResults()
gg.toast('已恢复')
break
end
end
end
--魔法商店结束

function wxyh()--无限烟花
gg.alert("请先使用烟花魔法或者衣柜，才能正常使用")
  tmp={}
  seaio(tmp,yanhuadz,4,5,true)
  gg.setValues(tmp)
  gg.addListItems(tmp)
  gg.toast("无限烟花开启成功")
end

function yxgq()--隐形钢琴
    if not gqaddr then
        gqaddr=searchaddr(4,"28,595",4,0x44,4,1,"-0x24","钢琴")
        if not gqaddr then return 0 end
    end
    local tmp={}
    seaio(tmp,gqaddr,4,1)
    seaio(tmp,gqaddr+0x6F84,4,257)
    gg.setValues(tmp)
end

function miaozuotan()--秒坐坛
suozishi(2)
end

function spfz()--手跑辅助
gg.toast("点击悬浮窗即可停下\n正在循环炸花点火中\n当前地图为"..map[X][3])
 while true do
  LightAFire() xianlazhuk() absorbCandlelight() A_LightChip()
   gg.setVisible(false)
   if gg.isVisible(true) then Main() break end
  end
end
--常用菜单结束

-----------------------------娱乐菜单---------------------------------
jdlzkg="-〘 ❌ 〙"
function jdlz()--巨大蜡烛
    gg.clearResults()
    gg.setRanges(4|-2080896)
    search("1,031,622,229", 4)
    local resultCount = gg.getResultCount()
    local result = gg.getResults(resultCount)
    local tmp = {}
    if jdlzkg=="-〘 ❌ 〙" then
    for j=1,3 do
    for i, v in ipairs(result) do
        seaio(tmp,v.address - 0x18-j*20+20,16,15)
        jdlzkg="-〘 ✅ 〙"
        gg.toast("进别的地图会闪退哦")
    end
    end
    else
    for j=1,3 do
    for i, v in ipairs(result) do
    seaio(tmp,v.address - 0x18-j*20+20,16,1)
    jdlzkg="-〘 ❌ 〙"
    end
    end
    end
    gg.setValues(tmp)
    end

grass={} 
zwszkg="-〘 ❌ 〙"
function zwsz()--植物生长
gg.clearResults()
if zwszkg=="-〘 ❌ 〙" then
gg.setRanges(8)
gg.searchNumber("1F;48Q::37",32)
gg.refineNumber("48",32)
res=gg.getResults(gg.getResultCount())
tmp={}
for i,v in pairs(res) do tmp[#tmp+1]={address=v.address-40,flags=16} end
tmp=gg.getValues(tmp)
for k,v in pairs(tmp) do
if v.value==1 then grass[1]={address=tmp[k].address+4,flags=16,value=10} grass[2]={address=tmp[k].address,flags=16,value=10} end end gg.setValues(grass) 
zwszkg="-〘 ✅ 〙"
else 
zwszkg="-〘 ❌ 〙"
grass[1].value=1 
grass[2].value=1 
gg.setValues(grass)
 end
end

rwyskg="-〘 ❌ 〙"
function rwys()--人物隐身
if rwyskg=="-〘 ❌ 〙" then
gg.addListItems({{address=rwysaddr,flags=16,freeze=true,value=0}}) rwyskg="-〘 ✅ 〙" else
gg.addListItems({{address=rwysaddr,flags=16,freeze=true,value=1}}) gg.clearList() end
end

rwdlkg="-〘 ❌ 〙"
function rwdl()--人物倒立+遁地
if rwdlkg=="-〘 ❌ 〙" then
tmp={
{flags=16,address=daoli,value=0,freeze=true},
{flags=16,address=daoli+16,value=-1,freeze=true},
{flags=4,address=daoli-0x4,value=3,freeze=true}
}
gg.setValues(tmp)
gg.addListItems(tmp)
rwdlkg="-〘 ✅ 〙" else
gg.clearList()
rwdlkg="-〘 ❌ 〙"
 end
end

function xgtq()--修改天气
if zhouyeaddr==nil then
zhouyeaddr = searchaddr(4,"500.0",16,"0x3C",16,"1","4","天气地址获取")
if zhouyeaddr == nil then return 0 end
end
tianqi=
{
{"午时",zhouyeaddr},
{"闪雷",zhouyeaddr+0x3F0},
{"深夜",zhouyeaddr+0x13B0},
{"早霞",zhouyeaddr+0x17A0},
{"黑夜",zhouyeaddr+0x1B90},
{"黄昏",zhouyeaddr+0x2760},
{"白天",zhouyeaddr+0x2B50},
}
tmp={}
for k,v in pairs(tianqi)do
  tmp[#tmp + 1] = {}
  tmp[#tmp] = tianqi[k][1]
end
  SN =gg.choice(tmp,{})
  if SN == nil then
  else
  tq={}
  for j = 1,7 do--清空天气
   seaio(tq,tianqi[j][2],4,0)
   end
      gg.setValues(tq)
      gg.setValues({{address = tianqi[SN][2], flags = 4, value = 1 }})
  end
end

function cxdj() --持续大叫
gg.setVisible(false)
gg.toast("再次点击关闭") 
while true do
Tab={}
Tab[1]={flags=4,value=1725047129,address=mfdz}
Tab[2]={flags=4,value=11,address=mfdz+0x3000}
Tab[3]={flags=4,value=-1404967393,address=mfdz+8,freeze=true}
gg.setValues(Tab)
gg.setVisible(false)
--gg.sleep(1000)
Tablo={{flags=4,value=0,address=mfdz+40,freeze=true}}
gg.setValues(Tablo)
gg.addListItems(Tablo)
if gg.isVisible(true) then 
gg.setVisible(false)
Tablo1={{flags=4,value=1,address=mfdz+40,freeze=false}} 
gg.setValues(Tablo1)
gg.addListItems(Tablo1)
gg.toast('已恢复') 
break 
end  
end 
end

function jsdz()----解锁动作  
    addr = searchaddr(4, "7454944414279221786", 32, "0x8", 4, "1702259015", "0x18", "解锁动作地址")
    z = {
        addr,
        addr - 0x2E0,
        addr - 0x5C0,
        addr - 0xB80,
        addr - 0xE60,
        addr - 0x19E0,
        addr - 0x1CC0,
        addr - 0x1FA0,
        addr - 0x2560,
        addr - 0x2840,
        addr - 0x2B20,
        addr - 0x2E00,
        addr - 0x3980,
        addr - 0x3F40,
        addr - 0x4220,
        addr - 0x4500,
        addr - 0x5080,
    }
    js = {}
    for j = 1, #z do
        seaio(js, z[j], 4, 0, true)
    end
    gg.addListItems(js)
    gg.toast("开启成功")
end

function M_yyjj()--试炼终点
  FX = "M_yyjj"
  local list_yyj = {
    "山谷入口",
    "向导先祖",
    "水试炼 终点",
    "️土试炼 终点",
    "气试炼 终点",
    "火试炼 终点",
    "返回主页"
  }
  local menu = gg.choice(list_yyj, nil, "预言季")
  if menu == 7 then
    jjrw()
  elseif menu ~= nil then
    Teleport(map_yyj[menu])
    gg.toast("瞬移到" .. list_yyj[menu])
  end
end

local ccmf
function lllz()--琉璃靓仔
gg.alert("必须使用魔法菜单-人物状态-闪耀魔法,否则功能无效果。")
if ccmf==nil then
ccmf = searchaddr(4,"8391179638569853300",32,"-0x10",4,"1045220557","0","璀璨魔法靓仔地址")
end
  tmp={}
  seaio(tmp,ccmf,16,"1048576",true)
  gg.setValues(tmp)
  gg.addListItems(tmp)
  gg.toast("开启成功")
  end

function bgxg()--曝光效果
hjys={}
guangaddr=searchaddr(8,"4,575,657,221,408,423,936",32,"-4",4,"64","12","光地址获取")
 hjys[1]={address=guangaddr,flags=16,freeze=true} 
 hjys[2]={address=guangaddr+4,flags=16,freeze=true} 
hjysyanshe=gg.prompt({
"环境曝光",
"光效调节",
},{
gg.getValues(hjys)[1].value,
gg.getValues(hjys)[2].value,
},{
"number",
"number",
})
hjys[1].value=hjysyanshe[1]
hjys[2].value=hjysyanshe[2]
gg.addListItems(hjys)
end

function mumuxfa(a,b,c)--测身高核心
tem=gg.getValues({[1]={address=a+b,flags=32}})[1].value
return tem + c
end
Shengdz = function() return mumuxfa(mumuxfa(rwdz,0x123CB4,0),0,0) end--好友身高核心

function cxsg()--查询身高
H = gg.getValues({{address = dz + 4, flags = 16}})[1].value
S = gg.getValues({{address = dz, flags = 16}})[1].value
height = 7.6 - 8.3*S - 3*H
height=string.format("%.3f",height)
Max = 7.6 - 8.3*S - 6
Min = 7.6 - 8.3*S + 6
Max=string.format("%.3f",Max)
Min=string.format("%.3f",Min)
if gg.alert("你的身高:"..height.."号\n最高身高:"..Max.."号\n最矮身高:"..Min.."号\n\n身高S值:"..S.."\n身高H值:"..H.."","确定","复制") == 2 then
gg.copyText("我的身高:"..height.."号\n最高身高:"..Max.."号\n最矮身高:"..Min.."号\n\n身高S值:"..S.."\n身高H值:"..H.."")
end
end

function hyxt()--好友系统
FX="hyxt"
--好友数量地址
if not friendsl then
friendsl=hyxx
if not friendsl then Main() return 0 end
end
local py=0x2c8
local sl=gg.getValues({{address = friendsl, flags = 4}})[1].value--好友数量
local firendname={}
for j=1,sl do
    local getname=""
    for i=1,22 do
            local tmp=gg.getValues({{address = friendsl+0x28+i+py*(j-1), flags = 1}})[1].value
            if tmp>=0 then--判断是否为中文
                getname=getname..string.char((tmp))
            else
                getname=getname..string.char((tmp+256))
            end
    end
    firendname[j]=getname
end

local Choice = gg.choice(firendname,{},"好友数量:"..sl.."位")
if Choice==nil then Main() return 0
elseif not Choice then return 0 end

--服装模块
function findbzid(id)
    --获取服饰名称
    for j = 1, 4 do
        for i, v in ipairs(bz_id[j]) do
            for l, j in ipairs(v) do
                if j[1] == id then
                    return j[2]
                end
            end
        end
    end
    return ""
end

--friendsl+0x28+0x23c 好友装扮 间隔2c8
local tmp={}
for i=1,5 do
    seaio(tmp,friendsl+0x28+0x23c+py*(Choice-1)+4*i-4,4)
end --多出一位
seaio(tmp,friendsl+0x28+0x23c+py*(Choice-1)+4*6,4)
tmp=gg.getValues(tmp)
fzname=""--服装名字
for i=1,6 do
    fzname=fzname..""..findbzid(tmp[i].value).."\n"
end

--体型模块
local tmp={}
for i=1,2 do
    seaio(tmp,friendsl+0x28+0x27c+py*(Choice-1)+4*i-4,16)
end
tmp=gg.getValues(tmp)
    local a,b,c,d,e 
    a={} a=tmp[1].value 
    b=tmp[2].value 
    c=7.6-8.3*a-3*b
    if(c<0) then  
        c=c*(-1) 
    end  
    d=1.6-8.3*a 
    if(d<0) then  
        d=d*(-1) 
    end
    d=math.modf(d)
    e=7.6-8.3*a-3*(-2) 
    if(e<0) then 
        e=e*(-1) 
    end
    e = math.modf(e)
    bin=gg.alert("好友名字:"..firendname[Choice].."\n好友身高:"..c.."号\n最高身高:"..d.."号\n最矮身高:"..e.."号\n身高S值:"..a.."\n身高H值:"..b.."\n\n服装:\n"..fzname,"确定","复制")
if bin==2 then gg.copyText("好友名字:"..firendname[Choice].."\n好友身高:"..c.."号\n最高身高:"..d.."号\n最矮身高:"..e.."号\n身高S值:"..a.."\n身高H值:"..b.."\n\n服装:\n"..fzname) end
end
--测身高结束

function hjhz()--皇家画质
  gg.setRanges(1048576)
  gg.searchNumber('1084227584',4)
  gg.getResults(9999)
  gg.editAll('0',4)
  gg.toast('换图即可恢复原状') 
  gg.clearResults()
end

yun={}
function ydcsh()--云朵初始化
  if pd==nil then
    yunaddr = searchaddr(4,"4489188110512422912",32,"24",16,"2.5","-0x2C","云地址获取")
    yun[1]={address=yunaddr,flags=16,freeze=true}
    yun[2]={address=yunaddr+4,flags=16,freeze=true}
    yun[3]={address=yunaddr+8,flags=16,freeze=true}
    pd=1
  end
end
function ydmh()--云朵美化
  ydcsh()
  ydys=gg.prompt({
    "❤️红色渲染️",
    "💚绿色渲染️",
    "💙蓝色渲染",
  },{
    gg.getValues(yun)[1].value,
    gg.getValues(yun)[2].value,
    gg.getValues(yun)[3].value,
  },{
    "number",
    "number",
    "number",
  })
  yun[1].value=ydys[1]
  yun[2].value=ydys[2]
  yun[3].value=ydys[3]
  gg.addListItems(yun)
end

function zhafang()--炸房
gg.alert("开启后10s内有效果，再次点击悬浮窗停止,不停止视为循环炸房。")
tmp={}
seaio(tmp,zf,16,41249,true)
gg.addListItems(tmp)
while true do
if gg.isVisible(true) then
gg.setVisible(false)
gg.clearList()
gg.clearResults()
gg.toast('已恢复')
break
end
end
end

 function thms()--土豪模式
TH = {
            {
              address =lazushuliang,--蜡烛
              flags = 4,
            },
                        {
              address =lazushuliang+8,--爱心
              flags = 4,
            },
                        {
              address =lazushuliang+0xC,--蜡烛充能
              flags = 4,
            },
                        {
              address =lazushuliang+0x3C,--季节蜡烛
              flags = 4,
            },
                        {
              address =lazushuliang+0x40,--季节蜡烛充能
              flags = 4,
            },
                        {
              address =lazushuliang+0x44,--献祭蜡烛
              flags = 4,
            },
                        {
              address =lazushuliang+0x4C,--季卡
              flags = 4,
            },
                        {
              address =lazushuliang+0x54,--季节心
              flags = 4,
            },
            
          }
    local MS = gg.prompt({
"蜡烛",
"爱心",
"蜡烛充能",
"季节蜡烛",
"季节蜡烛充能",
"献祭蜡烛",
"季卡",
"季节心",
},{
gg.getValues(TH)[1].value,
gg.getValues(TH)[2].value,
gg.getValues(TH)[3].value,
gg.getValues(TH)[4].value,
gg.getValues(TH)[5].value,
gg.getValues(TH)[6].value,
gg.getValues(TH)[7].value,
gg.getValues(TH)[8].value,
},{
"number",
"number",
"number",
"number",
"number",
"number",
"number",
"number",
  })
  if MS~= nil then
  for i=1,8 do
  TH[i].value= tonumber(MS[i])
  end
gg.setValues(TH)
end
end

--kk观光
function kkguanguang()
    if not shijiaoaddr then
        shijiaoaddr=searchaddr(4,2000,16,0xB8,16,2.5,"-0xB0","观光")
        if not shijiaoaddr then return 0 end
    end
        local menu=gg.prompt({
        "请设置无人机速度[1;10]",
        },{
        "1",
        true,
        },{
        "number",
        })
    if menu[1]=="" or not menu then return 0 end
    local ggsd=menu[1]
    gg.setVisible(false) 
    local tmp={}
    seaio(tmp,shijiaoaddr+0x44,16)
    seaio(tmp,shijiaoaddr+0x44+4,16)
    seaio(tmp,shijiaoaddr+0x44+8,16)
    x=gg.getValues(tmp)[1].value
    y=gg.getValues(tmp)[3].value
    z=gg.getValues(tmp)[2].value
    while true do
        local tmp={}
        seaio(tmp,shijiaoaddr+0x74+8,16)
        seaio(tmp,shijiaoaddr+0x74,16)
        local zy=gg.getValues(tmp)[1].value
        local cz=gg.getValues(tmp)[2].value/1.2*3.14
        x=x+ggsd*0.1*math.sin(zy)
        z=z+ggsd*0.1*math.sin(cz)
        y=y+ggsd*0.1*math.cos(zy)
        local tmp={}
        seaio(tmp,shijiaoaddr+0x44,16,x,true)
        seaio(tmp,shijiaoaddr+0x44+4,16,z,true)
        seaio(tmp,shijiaoaddr+0x44+8,16,y,true)
        gg.addListItems(tmp)
        gg.sleep(5)
        if gg.isVisible(true) then
           gg.setVisible(false) 
           if gg.alert("是否暂停无人机？","退出无人机","我要留在此地")==2 then
               gg.toast("点击修改器可再次启动")
               while not (gg.isVisible(true)) do end
               gg.setVisible(false) 
           else
               gg.removeListItems(tmp)
               return 0
           end
        end
    end
end
--娱乐结束

-- 菜单开始
qygkg="-〘 ❌ 〙"
function qyg()--全物品衣柜
--qygdz=so+0x3F151B ---全衣柜>>>
--gg.setConfig(2131427463,102)--对游戏隐藏23
if qygkg=="-〘 ✅ 〙" then
gg.setValues({{address=qygdz,flags=4,value=446629856}}) 

gg.clearList()
gg.toast("全衣柜关闭")
qygkg="-〘 ❌ 〙"
else
gg.setValues({{address=qygdz,flags=4,value=1386153952}})

gg.clearList()
--gg.setConfig(2131427463,110)--对游戏隐藏234
gg.toast("全衣柜已开")
qygkg="-〘 ✅ 〙"
end
end

wxhxkg="-〘 ❌ 〙"
function wxhx()--无限滑行
if wxhxkg=="-〘 ❌ 〙" then
--gg.setConfig(2131427463,102)--对游戏隐藏23
wxhxtab={}
seaio(wxhxtab,wxhxaddr,4,505925632,true)
gg.addListItems(wxhxtab)
gg.clearList()
wxhxkg="-〘 ✅ 〙" else
wxhxtab={}
seaio(wxhxtab,wxhxaddr,4,506073093,true)
gg.addListItems(wxhxtab)
gg.clearList()
--gg.setConfig(2131427463,110)--对游戏隐藏234
wxhxkg="-〘 ❌ 〙" end
end

bejkg="-〘 ❌ 〙"
function bej()--白耳机
--gg.setConfig(2131427463,102)--对游戏隐藏23
if bejkg=="-〘 ❌ 〙" then
gg.setValues({{address=bejaddr,flags=4,value=505712640}}) bejkg="-〘 ✅ 〙" else
gg.setValues({{address=bejaddr,flags=4,value=505873376}}) bejkg="-〘 ❌ 〙" 
--gg.setConfig(2131427463,110)--对游戏隐藏234
end
end

wshskg="-〘 ❌ 〙"
function wshs()--无视海水
--gg.setConfig(2131427463,102)--对游戏隐藏23
if wshskg=="-〘 ❌ 〙" then
gg.setValues({{address=wshsaddr,flags=4,value=506630144}})--无视
wshskg="-〘 ✅ 〙" else
gg.setValues({{address=wshsaddr,flags=4,value=505495552}})--有视
--gg.setConfig(2131427463, 14)--游戏隐藏234
wshskg="-〘 ❌ 〙" end
end

smlzkg="-〘 ❌ 〙"
function smlz()--睡眠粒子
if smlzkg=="-〘 ❌ 〙" then
GL(smlzaddr,4,257,true) smlzkg="-〘 ✅ 〙" else
GL(smlzaddr,4,1,false)
smlzkg="-〘 ❌ 〙" end
end

rwxzkg="-〘 ❌ 〙"
function rwxz()--人物旋转
if rwxzkg=="-〘 ❌ 〙" then
rwxz1=gg.prompt({"设置转速[0;100]"},{"100"},{"number"})
gg.addListItems({{address=rwxzaddr,flags=16,value=rwxz1[1],freeze=true}}) rwxzkg="-〘 ✅ 〙" else
gg.clearList() rwxzkg="-〘 ❌ 〙" end
end

tkfrkg="-〘 ❌ 〙"
function tkfr()--太空飞人
if tkfrkg=="-〘 ❌ 〙" then
tkr=gg.prompt({"设置太空人高度距离"},{"5"},{"number"})
if tkr[1]==nil then return end
  gg.addListItems({{address=tkfraddr,flags=16,freeze = true,value=tkr[1]}})
tkfrkg="-〘 ✅ 〙"
else gg.clearList() tkfrkg="-〘 ❌ 〙"
 end
end
---**-----*******9.29新增
xadlzkg="-〘 ❌ 〙"
function xadl()--xa点蜡烛
if xadlzkg=="-〘 ❌ 〙" then
gg.setValues({{address=xadlz,flags=4,value=-721215457}}) xadlzkg="-〘 ✅ 〙" else
gg.setValues({{address=xadlz,flags=4,value=872415464}})
xadlzkg="-〘 ❌ 〙" end
end

fqkg="-〘 ❌ 〙"
function xafq()--风墙
if fqkg=="-〘 ❌ 〙" then
gg.setValues({{address=fengqiang,flags=4,value=505873376}}) fqkg="-〘 ✅ 〙" else
gg.setValues({{address=fengqiang,flags=4,value=1847778369}})
fqkg="-〘 ❌ 〙" end
end

xayanhuakg="-〘 ❌ 〙"
function xayh()--烟花
if xayanhuakg=="-〘 ❌ 〙" then
gg.setValues({{address=xayanhua,flags=4,value=1895525739}}) xayanhuakg="-〘 ✅ 〙" else
gg.setValues({{address=xayanhua,flags=4,value=1895826762}})
xayanhuakg="-〘 ❌ 〙" end
end

unemotekg="-〘 ❌ 〙"
function xaemo()--全动作
if unemotekg=="-〘 ❌ 〙" then
gg.setValues({{address=unemote,flags=4,value=1384120352}}) unemotekg="-〘 ✅ 〙" else
gg.setValues({{address=unemote,flags=4,value=-1186976888}})
unemotekg="-〘 ❌ 〙" end
end

unclosetkg="-〘 ❌ 〙"
function xaqyg()--全衣柜
if unclosetkg=="-〘 ❌ 〙" then
gg.setValues({{address=uncloset,flags=4,value=1384120352}}) unclosetkg="-〘 ✅ 〙" else
gg.setValues({{address=uncloset,flags=4,value=446629856}})
unclosetkg="-〘 ❌ 〙" end
end

unnodeskg="-〘 ❌ 〙"
function xahys()--好友树
if unnodeskg=="-〘 ❌ 〙" then
gg.setValues({{address=unnodes,flags=4,value=1384120352}}) unnodeskg="-〘 ✅ 〙" else
gg.setValues({{address=unnodes,flags=4,value=872415336}})
unnodeskg="-〘 ❌ 〙" end
end

rcloudskg="-〘 ❌ 〙"
function xaqy()--去云朵
if rcloudskg=="-〘 ❌ 〙" then
gg.setValues({{address=rclouds,flags=4,value=0}}) rcloudskg="-〘 ✅ 〙" else
gg.setValues({{address=rclouds,flags=4,value=1}})
rcloudskg="-〘 ❌ 〙" end
end

rwaterkg="-〘 ❌ 〙"
function xaqs()--去家里海水
if rwaterkg=="-〘 ❌ 〙" then
gg.setValues({{address=rwater,flags=4,value=505581568}}) rwaterkg="-〘 ✅ 〙" else
gg.setValues({{address=rwater,flags=4,value=-506204171}})
rwaterkg="-〘 ❌ 〙" end
end

rportalskg="-〘 ❌ 〙"
function xaqcsm()--去传送门
if rportalskg=="-〘 ❌ 〙" then
gg.setValues({{address=rportals,flags=4,value=1384120352}}) rportalskg="-〘 ✅ 〙" else
gg.setValues({{address=rportals,flags=4,value=872415464}})
rportalskg="-〘 ❌ 〙" end
end

realisimkg="-〘 ❌ 〙"
function zshm()--真实画面
if realisimkg=="-〘 ❌ 〙" then
gg.setValues({{address=realisim,flags=4,value=1384120352}}) realisimkg="-〘 ✅ 〙" else
gg.setValues({{address=realisim,flags=4,value=872417320}})
realisimkg="-〘 ❌ 〙" end
end

pspeedkg="-〘 ❌ 〙"
function xabp()--奔跑速度
if pspeedkg=="-〘 ❌ 〙" then
gg.setValues({{address=pspeed,flags=16,value=8}}) pspeedkg="-〘 ✅ 〙" else
gg.setValues({{address=pspeed,flags=16,value=3.5}})
pspeedkg="-〘 ❌ 〙" end
end

pjumpkg="-〘 ❌ 〙"
function xaty()--跳远距离
if pjumpkg=="-〘 ❌ 〙" then
gg.setValues({{address=pjump,flags=4,value=505581568}}) pjumpkg="-〘 ✅ 〙" else
gg.setValues({{address=pjump,flags=4,value=505964577}})
pjumpkg="-〘 ❌ 〙" end
end

pdivekg="-〘 ❌ 〙"
function xayy()--游泳增强
if pdivekg=="-〘 ❌ 〙" then
gg.setValues({{address=pdive,flags=4,value=505712640}}) pdivekg="-〘 ✅ 〙" else
gg.setValues({{address=pdive,flags=4,value=-1118854912}})
pdivekg="-〘 ❌ 〙" end
end

pdelaykg="-〘 ❌ 〙"
function xahyrz()--幻影忍者
if pdelaykg=="-〘 ❌ 〙" then
gg.setValues({{address=pdelay,flags=4,value=1384120352}}) pdelaykg="-〘 ✅ 〙" else
gg.setValues({{address=pdelay,flags=4,value=872416009}})
pdelaykg="-〘 ❌ 〙" end
end

plainkg="-〘 ❌ 〙"
function xafj()--王子飞机模式
if plainkg=="-〘 ❌ 〙" then
gg.setValues({{address=plain,flags=4,value=1384120352}}) plainkg="-〘 ✅ 〙" else
gg.setValues({{address=plain,flags=4,value=872415402}})
plainkg="-〘 ❌ 〙" end
end

scooterkg="-〘 ❌ 〙"
function xahbx()--滑板鞋
if scooterkg=="-〘 ❌ 〙" then
gg.setValues({{address=scooter,flags=4,value=506892288}}) scooterkg="-〘 ✅ 〙" else
gg.setValues({{address=scooter,flags=4,value=1847647232}})
scooterkg="-〘 ❌ 〙" end
end

sdkg="-〘 ❌ 〙"
function rwsd()--滑板鞋
local xzy = A_Get_zero()
if sdkg=="-〘 ❌ 〙" then 
GL(rwzb[1].address,16,xzy[1],true) 
GL(rwzb[2].address,16,xzy[2],true) 
GL(rwzb[3].address,16.,xzy[3],true)
sdkg="-〘 ✅ 〙" else 
GL(rwzb[1].address,16,xzy[1],false) 
GL(rwzb[2].address,16,xzy[2],false) 
GL(rwzb[3].address,16,xzy[3],false)
sdkg="-〘 ❌ 〙" end
end

spflykg="-〘 ❌ 〙"
function xacjf()--超级飞
if spflykg=="-〘 ❌ 〙" then
gg.setValues({{address=spfly,flags=4,value=506761216}}) spflykg="-〘 ✅ 〙" else
gg.setValues({{address=spfly,flags=4,value=520725538}})
spflykg="-〘 ❌ 〙" end
end


wchargekg="-〘 ❌ 〙"
function xawxnl()--无限能量
if wchargekg=="-〘 ❌ 〙" then
gg.setValues({{address=wcharge,flags=4,value=505745408}}) wchargekg="-〘 ✅ 〙" else
gg.setValues({{address=wcharge,flags=4,value=505571328}})
wchargekg="-〘 ❌ 〙" end
end




function rwdx()--人物大小
local abc=gg.getValues({{address=dxbaddr,flags=16}})[1].value
gg.searchNumber(abc,16)
local efg=gg.getResults(5)
dabianaddr1=efg[1].address
dabianaddr2=efg[2].address
dabianaddr3=efg[3].address
dabianaddr4=efg[4].address
dabianaddr5=efg[5].address
foxprt=gg.prompt({"人物大小变"}, {""},{"number"})
gg.setValues({{address=dabianaddr1,flags=16,value=foxprt[1],freeze=true}})
gg.setValues({{address=dabianaddr2,flags=16,value=foxprt[1],freeze=true}})
gg.setValues({{address=dabianaddr3,flags=16,value=foxprt[1],freeze=true}})
gg.setValues({{address=dabianaddr4,flags=16,value=foxprt[1],freeze=true}})
gg.setValues({{address=dabianaddr5,flags=16,value=foxprt[1],freeze=true}})
end

xgjkg="-〘 ❌ 〙"
function xgj()--香港脚
if xgjkg=="-〘 ❌ 〙" then
gg.addListItems({{address=xgjaddr,flags=16,freeze=true,value=190}}) xgjkg="-〘 ✅ 〙" else
gg.clearList() xgjkg="-〘 ❌ 〙" end
end

--[[
function wszl()--无视重力
gg.searchNumber("1.0F;1.40129846e-45;3.0F::15", 16, false, gg.SIGN_EQUAL, 0, -1, 0)
gg.refineNumber("1.40129846e-45", 16, false, gg.SIGN_EQUAL, 0, -1, 0)
revert = gg.getResults(9999, nil, nil, nil, nil, nil, nil, nil, nil)
gg.editAll("20", 16)
gg.toast("快跑,🐮顿从棺材里爬出来了")
end
]]

function kzzl()--控制重力
kzzl1=gg.prompt({"设置重力[0为无视重力，1为默认重力][-15;15]"},{"1"},{"number"})
if kzzl1[1]==nil then return end
gg.addListItems({{address=kzzladdr,flags=16,freeze=true,value=kzzl1[1]}})
end

function tst()--踏尸跳
gg.addListItems({{address=kzzladdr,flags=16,value=-100,freeze=true}})
gg.sleep(500)
gg.clearList()
end

fmtkg="-〘 ❌ 〙"
function fmt()--飞毛腿
if fmtkg=="-〘 ❌ 〙" then
gg.addListItems({{address=fmtaddr,flags=16,freeze=true,value=5}}) fmtkg="-〘 ✅ 〙" else
gg.clearList() fmtkg="-〘 ❌ 〙" 
 end
end

function yjdd()--一键遁地
gg.clearResults()
gg.setRanges(4)
gg.searchNumber("1F;0~~0;65,537D::9",16)
gg.refineNumber("1",16)
gg.getResults(100)
gg.editAll("0",16)
gg.clearResults()
end
----- 菜单结束

--跑图开始
function PT1()
  qt(2)
  gg.toast("正在前往 [晨岛]")
  PTsleep(GTtime)
  PTSmall(PTtable[1][1][1],PTtable[1][1][2])
end

function PT2()
  qt(3)  
  gg.toast("正在前往 [云野]")  
  PTsleep(GTtime)  
  PTSmall(PTtable[2][1][1],PTtable[2][1][2])  
  csjc({-17.372812271118164, 171.26510620117188, -2.61037540435791},6)  
  PTSmall(PTtable[2][2][1],PTtable[2][2][2]) 
  csjc({-355.1221923828125, 128.1268768310547, 96.45269012451172},40) -- 传送2圣岛图入口
  PTSmall(PTtable[2][3][1],PTtable[2][3][2])
  csjc({271.6481018066406, 174.65869140625, -30.689847946166992},6) -- 传送2圣岛图出口
  csjc({-101.64898681640625, 185.3963623046875, 177.490966796875},4) -- 传送2图 2 入口
  csjc({167.26300048828125, 199.05149841308594, 220.2218780517578},5) -- 传送2图 1 左隐藏图入口
  PTSmall(PTtable[2][5][1],PTtable[2][5][2])
  csjc({242.37313842773438, 198.94761657714844, 227.39906311035156},4) -- 传送2图 1 左隐藏图出口
  PTSmall(PTtable[2][4][1],PTtable[2][4][2])
  csjc({132.1917266845703, 255.7042694091797, 486.8236083984375},8) -- 2二图去2终点图
  PTSmall(PTtable[2][6][1],PTtable[2][6][2])
  gg.toast("[云野] 结束")
end

-- 雨林跑图
function PT3()
  PTGY(300)
  qt(9) 
  gg.toast("正在前往 [雨林]")
  PTsleep(GTtime)
  PTSmall(PTtable[3][1][1],PTtable[3][1][2])
  csjc({29.446800231933594, 98.68903350830078, -108.74456024169922},10) -- 雨林图 2 入口
  PTSmall(PTtable[3][2][1],PTtable[3][2][2])
  csjc({-5.01580918818712234;114.32728576660156;-54.55448913574219},11) -- 雨林图 2 右隐藏图入口
  PTSmall(PTtable[3][3][1],PTtable[3][3][2])
  csjc({54.191062927246094, 54.770408630371094, 43.37236785888672},12) -- 地底隐藏图入口
  PTSmall(PTtable[3][4][1],PTtable[3][4][2])
  csjc({-57.56206130981445, 210.17996215820312, -283.5279541015625},11) -- 地底隐藏图出口
  csjc({17.838523864746094, 87.8037338256836, 124},13) -- 隐藏图进雨林图 3
  PTSmall(PTtable[3][5][1],PTtable[3][5][2])
  csjc({-17.36788558959961, 182.655517578125, 402.27899169921875},14) -- 进入雨林宫殿
  PTSmall(PTtable[3][6][1],PTtable[3][6][2])
  gg.toast("[雨林] 结束")
end

-- 5跑图
function PT4()
  qt(15)
  gg.toast("正在前往 [霞谷]")
  PTsleep(GTtime)
  PTSmall(PTtable[4][1][1],PTtable[4][1][2])
  csjc({206.29270935058594, 57.820106506347656, -604.9664916992188},16) -- 霞光城入口
  PTSmall(PTtable[4][2][1],PTtable[4][2][2])
  csjc({204.70770263671875, 491.51055908203125, -205.14031982421875},17) -- 飞行赛道入口
  PTSmall(PTtable[4][3][1],PTtable[4][3][2])
  csjc({60.74193572998047, 137.8476104736328, -292.3225402832031},20) -- 5终点门入口
  PTSmall(PTtable[4][4][1],PTtable[4][4][2])
  PTsleep(GTtime)
  mxjpt()--梦想季
  gg.toast("[霞谷]] 结束")
end

-- 3跑图
function PT5()
PTGY(300)
  qt(21)
  gg.toast("正在前往 [墓土]")
  PTsleep(GTtime)
  PTSmall(PTtable[5][1][1],PTtable[5][1][2])
  Teleport({-210.83389282226562, 43.8532829284668, -825.1362915039062}) -- 进漩涡
  gg.sleep(25000)
  PTSmall(PTtable[5][2][1],PTtable[5][2][2])
  csjc({-93.77214813232422, 11.91988754272461, 156.5588836669922},24) -- 进图 3
  PTSmall(PTtable[5][3][1],PTtable[5][3][2])
  csjc({192.6549835205078, 68.13046264648438, -72.91191864013672},25) -- 进沉船
  PTSmall(PTtable[5][4][1],PTtable[5][4][2])
  csjc({-349.27203369140625, 34.950706481933594, 387.2141418457031},26) -- 进古战场
  PTSmall(PTtable[5][5][1],PTtable[5][5][2])
  csjc({-289.4688415527344, 93.0536117553711, -404.3544921875},27) -- 进终点
  PTSmall(PTtable[5][6][1],PTtable[5][6][2])
  gg.toast("[墓土] 结束")
end


-- 3跑图
function PT6()
gg.toast("正在前往 [禁阁]")
  qt(28)
  PTsleep(GTtime)
  csjc({-42.6407585144043, 38.3612060546875, -98.20526123046875},29)
  xianlazhuk()
  PTSmall(PTtable[6][2][1],PTtable[6][2][2])
  csjc({40.35205459595, 541.86962890625, -25.08329963684},28)
  xianlazhuk()
  PTSmall(PTtable[6][1][1],PTtable[6][1][2])
  gg.toast("正在进入 [四楼]")
  csjc({-0.1043953374, 214.60452270508, 2.59286475182},30)
  xianlazhuk()
  PTSmall(PTtable[6][3][1],PTtable[6][3][2])
  gg.toast("[禁阁] 结束")
end

function PT7()
  gg.toast("正在前往办公室")
  qt(32)
  LightAFire()
  for i=1,3 do Teleport(mapbgs[i]) gg.sleep(450) end
  PTsleep(4000)
end

function PT8()
  qt(23)
  gg.toast("正在前往方舟")
  PTSmall(PTtable[5][7][1],PTtable[5][7][2])
  PTsleep(4000)
end

function mxjpt()
  gg.toast("前往梦想季地图")
  for i=1,2 do
    qt(45+i)
    gg.sleep(1000)
    Teleport(mapmxj[i])
    yijian() 
    gg.toast("过图时间为5s请耐心等待")
    PTsleep(5000)
  end
end
function PT9()
  gg.toast("前往云野八人门")
  qt(7)
  gg.sleep(1000)
  xianlazhuk()
  gg.sleep(1000)
  LightAFire()
  Teleport({-5.740689754486084;39.69737243652344;-2.422407627105713}) gg.sleep(1000)
  Teleport({-26.520200729370117, 58.828182220458984, -44.88513946533203}) --(八人门山顶蜡烛）
  absorbCandlelight()
  PTsleep(3000)
end

function PT10()
  gg.toast("前往试炼地图")
  for i=1,5 do
    qt(40+i)
    gg.sleep(1000)
    Teleport(map_yyj[1+i])
    gg.sleep(1000)
    xianlazhuk()
    absorbCandlelight()
    gg.toast("过图时间为10s请耐心等待")
    PTsleep(10000)
  end
end

function PT11()
  for i=1,2 do
    qt(32+i)
    xianlazhuk()
    absorbCandlelight()
    PTsleep(5000)
  end
end

function PT12()
  qt(37)
  gg.sleep(2000)
  xianlazhuk()
  absorbCandlelight()
  gg.sleep(2000)
  qt(33)
  PTsleep(5000)
end

function PT13()
qt(55)
PTSmall(PTtable[7][1][1],PTtable[7][1][2])
end

function PT14()--飞行赛道
gg.toast("前往飞行赛道")
qt(17)
gg.sleep(4000)
Teleport({166.4430389404297;1187.055908203125;398.1310729980469})
LightAFire() 
miaozuotan()
gg.sleep(18000)
Teleport({81.03201293945312;1184.539794921875;365.4808044433594})
gg.sleep(500)
Teleport({-399.22747802734375;1164.7938232421875;72.19680786132812})
gg.sleep(500)
Teleport({152.20596313476562;1014.4254760742188;-97.61978912353516})
gg.sleep(8000)
Teleport({48.35710525512695;166.03041076660156;-0.13530772924423218})
gg.sleep(3000)
Teleport({57.89421081542969;132.8519744873047;-219.01834106445312})
gg.sleep(8000)
A_LightChip()
gg.sleep(20000)
end

function PT15()
  gg.toast("前往滑雪赛道")
  qt(15)
  PTsleep(4000)
  Teleport({290.24816894531, 39.45797729492, -527.30267333984})
  gg.sleep(10000)
  LightAFire()
  Teleport({163.92190551757812;934.9786376953125;662.388671875})
  gg.sleep(1000)
  miaozuotan()
  gg.sleep(18000)
  Teleport({208.15991210938, 617.72698974609, -447.23425292969})
  gg.sleep(1000)
  Teleport({256.20028686523, 585.98559570312, -564.76477050781})
  gg.sleep(10000)
  Teleport({54, 155, -138})
  Teleport({58.34699630737305;138.28443908691406;-218.4073944091797})
  gg.sleep(2000)
  for i=1,7 do
    gg.sleep(2000)
    A_LightChip()
  end
  gg.toast("收完蜡烛可以走了")
end

------------------以下为线性单图-------------------

function chendao()--晨岛
qt(2)
xianlazhuk() LightAFire()
xxtpset()
for i=1,#map1 do
xxtp(map1[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<晨岛>结束")
end
function yunye()--云野
local fs=gg.choice(
        {"云野一图","云野二图","云野左图","云野右图","云野宫殿","云野圣岛","↩️"},{})
if fs == 1 then yunye1() end
if fs == 2 then yunye2() end
if fs == 3 then yunye3() end
if fs == 4 then yunye4() end
if fs == 5 then yunye5() end
if fs == 6 then yunye6() end
if fs == 7 then xxpt() end
end
function yunye1()--云野一图
qt(3)
xianlazhuk() LightAFire()
xxtpset()
for i=1,#map2 do
xxtp(map2[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<云野一图>结束")
end
function yunye2()--云野二图
qt(4)
xianlazhuk() LightAFire()
xxtpset()
for i=1,#map5 do
xxtp(map5[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<云野二图>结束")
end
function yunye3()--云野左隐藏图
qt(5)
xianlazhuk() LightAFire()
xxtpset()
for i=1,#map6 do
xxtp(map6[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<云野左隐藏图>结束")
end
function yunye4()--云野右隐藏图
qt(6)
xianlazhuk() LightAFire()
xxtpset()
for i=1,#map3 do
xxtp(map3[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<云野右隐藏图>结束")
end
function yunye5()--云野宫殿
qt(8)
xianlazhuk() LightAFire()
xxtpset()
for i=1,#map7 do
xxtp(map7[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<云野宫殿>结束")
end
function yunye6()--云野圣岛
qt(40)
xianlazhuk() LightAFire()
xxtpset()
for i=1,#map4 do
xxtp(map4[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<云野圣岛>结束")
end
function yulin()--雨林
local fs=gg.choice(
        {"雨林一图","雨林二图","雨林隐藏图","雨林地底图","雨林水母图","雨林终点图","风行季地图","↩️"},{}
        )
if fs == 1 then yulin1() end
if fs == 2 then yulin2() end
if fs == 3 then yulin3() end
if fs == 4 then yulin4() end
if fs == 5 then yulin5() end
if fs == 6 then yulin6() end
if fs == 7 then yulin7() end
if fs == 8 then xxpt() end
end
function yulin1()--雨林一图
qt(9)
xianlazhuk() LightAFire()
xxtpset()
for i=1,#map8 do
xxtp(map8[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<雨林一图>结束")
end
function yulin2()--雨林二图
qt(10)
xianlazhuk() LightAFire()
xxtpset()
for i=1,#map9 do
xxtp(map9[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<雨林二图>结束")
end
function yulin3()--雨林隐藏图
qt(11)
xianlazhuk() LightAFire()
xxtpset()
for i=1,#map10 do
xxtp(map10[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<雨林隐藏图>结束")
end
function yulin4()--雨林地底图
qt(12)
xianlazhuk() LightAFire()
xxtpset()
for i=1,#map11 do
xxtp(map11[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<雨林地底图>结束")
end
function yulin5()--雨林水母图
qt(13)
xianlazhuk() LightAFire()
xxtpset()
for i=1,#map12 do
xxtp(map12[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<雨林水母图>结束")
end
function yulin6()--雨林终点图
qt(14)
xianlazhuk() LightAFire()
xxtpset()
for i=1,#map13 do
xxtp(map13[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<雨林终点图>结束")
end
function yulin7()--风行季
qt(55)
xianlazhuk() LightAFire()
xxtpset()
for i=1,#map29 do
xxtp(map29[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<飞行季>结束")
end
function xiagu()--霞谷
local fs=gg.choice(
        {"霞谷一图","霞光城","霞谷宫殿","↩️"},{}
        )
if fs == 1 then xiagu1() end
if fs == 2 then xiagu2() end
if fs == 3 then xiagu4() end
if fs == 4 then xxpt() end
end
function xiagu1()--霞谷一图
qt(15)
xianlazhuk() LightAFire()
xxtpset()
for i=1,#map14 do
xxtp(map14[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<霞谷一图>结束")
end
function xiagu2()--霞光城
qt(16)
xianlazhuk() LightAFire()
xxtpset()
for i=1,#map15 do
xxtp(map15[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<霞光城>结束")
end
function xiagu4()--霞谷宫殿
qt(20)
xianlazhuk() LightAFire()
xxtpset()
for i=1,#map17 do
xxtp(map17[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<霞谷宫殿>结束")
end
function mutu()--墓土
local fs=gg.choice(
        {"墓土一图","墓土二图","墓土五龙图","墓土沉船图","墓土古战场","墓土宫殿","墓土方舟","↩️"}
        )
if fs == 1 then mutu1() end
if fs == 2 then mutu2() end
if fs == 3 then mutu3() end
if fs == 4 then mutu4() end
if fs == 5 then mutu5() end
if fs == 6 then mutu6() end
if fs == 7 then mutu7() end
if fs == 8 then xxpt() end
end
function mutu1()--墓土一图
qt(21)
xianlazhuk() LightAFire()
xxtpset()
for i=1,#map18 do
xxtp(map18[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<墓土一图>结束")
end
function mutu2()--墓土二图
qt(22)
xianlazhuk() LightAFire()
xxtpset()
for i=1,#map19 do
xxtp(map19[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<墓土二图>结束")
end
function mutu3()--墓土五龙图
qt(24)
xianlazhuk() LightAFire()
xxtpset()
for i=1,#map20 do
xxtp(map20[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<墓土五龙图>结束")
end
function mutu4()--墓土沉船图
qt(25)
xianlazhuk() LightAFire()
xxtpset()
for i=1,#map21 do
xxtp(map21[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<墓土沉船图>结束")
end
function mutu5()--墓土古战场
qt(26)
xianlazhuk() LightAFire()
xxtpset()
for i=1,#map22 do
xxtp(map22[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<墓土古战场>结束")
end
function mutu6()--墓土宫殿
qt(27)
xianlazhuk() LightAFire()
xxtpset()
for i=1,#map23 do
xxtp(map23[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<墓土宫殿>结束")
end
function mutu7()--墓土方舟
qt(23)
xianlazhuk() LightAFire()
xxtpset()
for i=1,#map27 do
xxtp(map27[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<墓土方舟>结束")
end
function jinge()--禁阁
local fs=gg.choice(
        {"禁阁右隐藏图","禁阁低层","禁阁高层","办公室","星光沙漠","沉船海滩","瓶子洞口","↩️"},{}
        )
if fs == 1 then jinge1() end
if fs == 2 then jinge2() end
if fs == 3 then jinge3() end
if fs == 4 then jinge7() end
if fs == 5 then jinge4() end
if fs == 6 then jinge5() end
if fs == 7 then jinge6() end
if fs == 8 then xxpt() end
end
function jinge1()--禁阁右隐藏图
qt(29)
xianlazhuk() LightAFire()
xxtpset()
for i=1,#map24 do
xxtp(map24[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<禁阁右隐藏图>结束")
end
function jinge2()--禁阁底层
qt(28)
xianlazhuk() LightAFire()
xxtpset()
for i=1,#map25 do
xxtp(map25[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<禁阁底层>结束")
end
function jinge3()--禁阁高层
qt(30)
xianlazhuk() LightAFire()
xxtpset()
for i=1,#map26 do
xxtp(map26[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<禁阁高层>结束")
end
function jinge4()--王子季星光沙漠
qt(50)
xianlazhuk() LightAFire()
xxtpset()
for i=1,#map30 do
xxtp(map30[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<星光沙漠>结束")
end
function jinge5()--沉船海滩
qt(51)
xianlazhuk() LightAFire()
xxtpset()
for i=1,#map31 do
xxtp(map31[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<沉船海滩>结束")
end
function jinge6()--瓶子洞口
qt(52)
xianlazhuk() LightAFire()
xxtpset()
for i=1,#map32 do
xxtp(map32[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<瓶子洞口>结束")
end
function jinge7()--办公室
qt(32)
xianlazhuk() LightAFire()
xxtpset()
for i=1,#mapbgs do
xxtp(mapbgs[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<办公室>结束")
end
function xiagulazhu()--小图查漏补缺
PT15()
gg.setVisible(true)
end
--------------------线性单图完毕----------------------

------------------以下为线性全图----------------
function chend()--晨岛
qt(2)
xianlazhuk() LightAFire()
for i=1,#map1 do
xxtp(map1[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<晨岛>结束")
end
function yuny()--云野
local fs=gg.choice(
        {"云野一图","云野二图","云野左图","云野右图","云野宫殿","云野圣岛","↩️"},{}
        )
if fs == 1 then yuny1() end
if fs == 2 then yuny2() end
if fs == 3 then yuny3() end
if fs == 4 then yuny4() end
if fs == 5 then yuny5() end
if fs == 6 then yuny6() end
if fs == 7 then xxpt() end
end
function yuny1()--云野一图
qt(3)
xianlazhuk() LightAFire()
for i=1,#map2 do
xxtp(map2[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<云野一图>结束")
end
function yuny2()--&
qt(4)
xianlazhuk() LightAFire()
for i=1,#map5 do
xxtp(map5[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<云野二图>结束")
end
function yuny3()--云野左隐藏图
qt(5)
xianlazhuk() LightAFire()
for i=1,#map6 do
xxtp(map6[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<云野左隐藏图>结束")
end
function yuny4()--云野右隐藏图
qt(6)
xianlazhuk() LightAFire()
for i=1,#map3 do
xxtp(map3[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<云野右隐藏图>结束")
end
function yuny5()--云野宫殿
qt(8)
xianlazhuk() LightAFire()
for i=1,#map7 do
xxtp(map7[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<云野宫殿>结束")
end
function yuny6()--云野圣岛
qt(40)
xianlazhuk() LightAFire()
for i=1,#map4 do
xxtp(map4[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<云野圣岛>结束")
end
function yul()--雨林
local fs=gg.choice(
        {"雨林一图","雨林二图","雨林隐藏图","雨林地底图","雨林水母图","雨林终点图","风行季地图","↩️"}
        )
if fs == 1 then yul1() end
if fs == 2 then yul2() end
if fs == 3 then yul3() end
if fs == 4 then yul4() end
if fs == 5 then yul5() end
if fs == 6 then yul6() end
if fs == 7 then yul7() end
if fs == 8 then xxpt() end
end
function yul1()--雨林一图
qt(9)
xianlazhuk() LightAFire()
for i=1,#map8 do
xxtp(map8[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<雨林一图>结束")
end
function yul2()--雨林二图
qt(10)
xianlazhuk() LightAFire()
for i=1,#map9 do
xxtp(map9[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<雨林二图>结束")
end
function yul3()--雨林隐藏图
qt(11)
xianlazhuk() LightAFire()
for i=1,#map10 do
xxtp(map10[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<雨林隐藏图>结束")
end
function yul4()--雨林地底图
qt(12)
xianlazhuk() LightAFire()
for i=1,#map11 do
xxtp(map11[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<雨林地底图>结束")
end
function yul5()--雨林水母图
qt(13)
xianlazhuk() LightAFire()
for i=1,#map12 do
xxtp(map12[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<雨林水母图>结束")
end
function yul6()--雨林终点图
qt(14)
xianlazhuk() LightAFire()
for i=1,#map13 do
xxtp(map13[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<雨林终点图>结束")
end
function yul7()--风行季
qt(55)
xianlazhuk() LightAFire()
for i=1,#map29 do
xxtp(map29[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<飞行季>结束")
end
function xiag()--霞谷
local fs=gg.choice(
        {"霞谷一图","霞光城","霞谷宫殿","↩️"}
        )
if fs == 1 then xiag1() end
if fs == 2 then xiag2() end
if fs == 3 then xiag4() end
if fs == 4 then xxpt() end
end
function xiag1()--霞谷一图
qt(15)
xianlazhuk() LightAFire()
for i=1,#map14 do
xxtp(map14[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<霞谷一图>结束")
end
function xiag2()--霞光城
qt(16)
xianlazhuk() LightAFire()
for i=1,#map15 do
xxtp(map15[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<霞光城>结束")
end
function xiag4()--霞谷宫殿
qt(20)
xianlazhuk() LightAFire()
for i=1,#map17 do
xxtp(map17[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<霞谷宫殿>结束")
end
function mut()--墓土
local fs=gg.choice(
        {"墓土一图","墓土二图","墓土五龙图","墓土沉船图","墓土古战场","墓土宫殿","墓土方舟","↩️"},{}
        )
if fs == 1 then mut1() end
if fs == 2 then mut2() end
if fs == 3 then mut3() end
if fs == 4 then mut4() end
if fs == 5 then mut5() end
if fs == 6 then mut6() end
if fs == 7 then mut7() end
if fs == 8 then xxpt() end
end
function mut1()--墓土一图
qt(21)
xianlazhuk() LightAFire()
for i=1,#map18 do
xxtp(map18[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<墓土一图>结束")
end
function mut2()--墓土二图
qt(22)
xianlazhuk() LightAFire()
for i=1,#map19 do
xxtp(map19[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<墓土二图>结束")
end
function mut3()--墓土五龙图
qt(24)
xianlazhuk() LightAFire()
for i=1,#map20 do
xxtp(map20[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<墓土五龙图>结束")
end
function mut4()--墓土沉船图
qt(25)
xianlazhuk() LightAFire()
for i=1,#map21 do
xxtp(map21[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<墓土沉船图>结束")
end
function mut5()--墓土古战场
qt(26)
xianlazhuk() LightAFire()
for i=1,#map22 do
xxtp(map22[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<墓土古战场>结束")
end
function mut6()--墓土宫殿
qt(27)
xianlazhuk() LightAFire()
for i=1,#map23 do
xxtp(map23[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<墓土宫殿>结束")
end
function mut7()--墓土方舟
qt(23)
xianlazhuk() LightAFire()
for i=1,#map27 do
xxtp(map27[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<墓土方舟>结束")
end
function jing()--禁阁
local fs=gg.choice(
        {"禁阁右隐藏图","禁阁低层","禁阁高层","办公室","星光沙漠","沉船海滩","瓶子洞口","↩️"},{}
        )
if fs == 1 then jing1() end
if fs == 2 then jing2() end
if fs == 3 then jing3() end
if fs == 4 then jing7() end
if fs == 5 then jing4() end
if fs == 6 then jing5() end
if fs == 7 then jing6() end
if fs == 8 then xxpt() end
end
function jing1()--禁阁右隐藏图
qt(29)
xianlazhuk() LightAFire()
for i=1,#map24 do
xxtp(map24[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<禁阁右隐藏图>结束")
end
function jing2()--禁阁底层
qt(28)
xianlazhuk() LightAFire()
for i=1,#map25 do
xxtp(map25[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<禁阁底层>结束")
end
function jing3()--禁阁高层
qt(30)
xianlazhuk() LightAFire()
for i=1,#map26 do
xxtp(map26[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<禁阁高层>结束")
end
function jing4()--王子季星光沙漠
qt(50)
xianlazhuk() LightAFire()
for i=1,#map30 do
xxtp(map30[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<星光沙漠>结束")
end
function jing5()--沉船海滩
qt(51)
xianlazhuk() LightAFire()
for i=1,#map31 do
xxtp(map31[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<沉船海滩>结束")
end
function jing6()--瓶子洞口
qt(52)
xianlazhuk() LightAFire()
for i=1,#map32 do
xxtp(map32[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<瓶子洞口>结束")
end
function jing7()--办公室
qt(32)
xianlazhuk() LightAFire()
for i=1,#mapbgs do
xxtp(mapbgs[i])
end
absorbCandlelight()
jiasu(1)
gg.toast("线性跑图<办公室>结束")
end
-------------------线性全图完毕--------------------

function xxpt()--线性跑图菜单
FX="xxpt"
     local menu = gg.choice({
      "自动", "晨岛", "云野", "雨林", "霞谷",
        "墓土", "禁阁","返回"
    },{})
    if menu == 1 then xxqt() end
    if menu == 2 then chendao() end
    if menu == 3 then yunye() end
    if menu == 4 then yulin() end
    if menu == 5 then xiagu() end
    if menu == 6 then mutu() end
    if menu == 7 then jinge() end
    if menu == 8 then pt() end
end

function xxqt()--自动线性全图
xxtpset() chend() yuny1() yuny2() yuny3() yuny4() yuny5() yuny6() yul1() yul2() yul3() yul4() yul5() yul6() yul7() xiag1() xiag2() xiag4() mut1() mut2() mut3() mut4() mut5() mut6() mut7() jing1() jing2() jing3() jing4() jing5() jing6() jing7() 
PT10() mxjpt()
end

function qzdpt() --全自动跑图
  local ptmenu = gg.multiChoice(
  {
    "自动",  
    "晨岛",  
    "云野",  "雨林",  "霞谷", "暮土", "禁阁", "办公室",
      "遗忘方舟️", "云野八人门", "预言试炼", "伊旬",
      "重生之路",'遇境马里奥',"霞谷蜡烛"})
   v1=os.date("%H%M")
  if ptmenu~=nil then 
    if ptmenu[1]==true then    
      for i=1,15 do  ptmenu[i]=true       
      end      
    end      
  for i=2,15 do  
      if ptmenu[i]==true then 
      gg.clearResults()
    gg.clearList()
        doAction("PT"..(i-1))  
      yijian()
      gg.clearResults()
  gg.clearList()
      end      
  end
   qt(1)  
   xianlazhuk()
   absorbCandlelight()            
   v2=os.date("%H%M")
   shikl= v2-v1
   gg.alert("全自动跑图耗时"..shikl.."分钟")
  end
end

function fcs(dtid) --地图id，tmp1-5和蜡烛sz第一个相同
py={-0x21CD3C,-0x2225BC,-0x24CC9C,-0x24D000,-0x24D904}
tmp={}
for i=1,5 do
seaio(tmp,rwdz+py[i],4,dtid)
--gg.addListItems(tmp)
tmp1 = {
        {
            address = rwdz+py[i],
            flags = 4,
            name = 'dtid',
        },

        }
--gg.addListItems(tmp1)
end
gg.setValues(tmp)
ptpd=0
while  gg.getValues(dqwzaddr)[1].value~=dtid 
do


ptpd=ptpd+1 

if ptpd>11 and 
gg.getValues({{address=rwdz+py[2],flags = 4  }})[1].value==dtid 
then 
local hh=gg.getValues({{address=rwdz+py[2],flags = 4  }})[1].value
gg.setValues({{address=dtaddr,flags = 4 ,value= hh }}) 
break 
end

end
end
function ydpt()---原地跑图地图判断往下偏移一直+4  32个遍历sz第二个开始
qt(52)
jiasu(100)
gg.sleep(1)
time=os.time()
local sendid,Dc={},{}
for i, v in pairs(resulta) do
fcs(v[1])
for k=0, (#v-1)/32 do
gg.toast("地图进度  :  "..i.." / "..#resulta.."\n当前图烛光  :  "..((k+1)*100/((#v-1)/32+1)).." % ",true)
for j=1,32 do
sendid[j]={address=dtaddr+j*4 ,flags = 4 ,value=v[j+(1+k*32)] or 0 }
offseters1 = {
        {
            address = dtaddr+j*4,
            flags = 4,
            name = 'sendid',
        },

        }
--gg.addListItems(offseters1)
end
gg.sleep(1)
gg.setValues(sendid)

Dc[1]={address=dtaddr+34*4-4 ,flags = 4 ,value=32}--赋值32吸蜡烛后自动变0
offseters2 = {
        {
            address = dtaddr+34*4-4,
            flags = 4,
            name = 'Dc1',
        },

        }
--gg.addListItems(offseters2)
gg.setValues(Dc)
while true do
Dc=gg.getValues(Dc)

if Dc[1].value==0 then
break
end
end      
end
end
gg.toast("用时:  "..os.time()-time.."秒")
qt(1)
end

function bzdpt()--半自动跑图
local i=2
local k=40
x3=os.date("%M%S")
while i<=33 do
local ccc=gg.choice({'下一个','返回主页'},{})
if ccc == nil or ccc == 1 then
renyimen(i)
gg.sleep(6000)
yijian()
gg.sleep(1000)
i=i+1
gg.clearResults()
gg.clearList()
else
x5=os.date("%M%S")
jk= x5-x3
gg.alert("半自动跑图已停止，耗时"..jk.."秒")
Main()
 return
end
end

while k<=53 do
local ccc=gg.choice({'下一个','返回主页'},{})
if ccc == nil or ccc == 1 then 
renyimen(k)
gg.sleep(6000)
yijian()
gg.sleep(1000)
k=k+1
else 
x6=os.date("%M%S")
dj= x6-x3
gg.alert("半自动跑图已停止，耗时"..dj.."秒")
Main()
return
end
renyimen(1)
sleep(3000)
yijian()
gg.clearResults()
gg.clearList()
end	
x4=os.date("%M%S")
bzd= x4-x3
gg.alert("半自动跑图耗时"..bzd.."秒")
end

function xbzdpt()--新半自动跑图
local i=2
local k=40
x1=os.date("%M%S") 
while i<=33 do
renyimen(i)
gg.sleep(6000)
yijian()
gg.sleep(1000)
i=i+1
gg.clearResults()
gg.clearList()
if gg.isVisible(true) then gg.setVisible(false)
xbzdptzt=gg.alert("是否暂停新半自动跑图？","是","否")
if xbzdptzt==1 then renyimen(1)
return end end
end

while k<=53 do
renyimen(k)
gg.sleep(6000)
yijian()
gg.sleep(1000)
k=k+1
gg.clearResults()
gg.clearList()
if gg.isVisible(true) then gg.setVisible(false)
xbzdptzt=gg.alert("是否暂停新半自动跑图？","是","否")
if xbzdptzt==1 then renyimen(1)
return end end
end	
x2=os.date("%M%S") 
  sj= x2-x1  
  gg.alert("新半自动跑图耗时"..sj.."秒") 
renyimen(1)
end

function jkpt()-- 跑图
local i=2
local k=40
c3=os.date("%M%S") 
while i<=33 do
renyimen(i)
gg.sleep(3500)
jkptyj()
gg.sleep(1000)
i=i+1
gg.clearResults()
gg.clearList()
data=i
if gg.isVisible(true) then gg.setVisible(false)
jkptzt=gg.alert("是否暂停 跑图？","是","否")
if jkptzt==1 then renyimen(1)
return end end
end

while k<=53 do
renyimen(k)
gg.sleep(3500)
jkptyj()
gg.sleep(1000)
k=k+1
gg.clearResults()
gg.clearList()
if gg.isVisible(true) then gg.setVisible(false)
jkptzt=gg.alert("是否暂停 跑图？","是","否")
if jkptzt==1 then renyimen(1)
return end end
end	
c4=os.date("%M%S") 
  syj= c4-c3
  gg.alert(" 跑图完毕,耗时"..syj.."秒") 
renyimen(1)
end

function xglz()--霞谷蜡烛
js=os.date("%M%S")
PT14() PT15()
nd=os.date("%M%S")
shf=nd-js
gg.alert("霞谷蜡烛完成,耗时"..shf.."秒")
end

function ydrwxf()--原地任务修复工具
gg.alert("本功能只能使用一次并且是给不能正常使用原地任务和手动做任务的人用的\n请不要出于好奇而去作死\n使用之后第二天即可恢复正常")
tmp,tm={},{}
for i=1,309 do
tmp[i]={flags=16,address=ydrwddr+i*8,value=0}
end
for i=1,309 do
tm[i]={flags=4,address=ydrwcd+i*4,value=i}
end
gg.setValues(tmp)
gg.setValues(tm)
end
mrrwid = {}
function finishites()
    local tmp2 = {}
    for i = 1, 309 do
        tmp2[i] = { address = mrrw + 4 + (mrrwid[i] - 1) * 8, flags = 16,name='1tmp2'..i }
       -- gg.addListItems(tmp2)
       -- print (gg.getValues(tmp2))
    end
    tmp2 = gg.getValues(tmp2)
    for i = 1, 309 do
        tmp2[i].value = tmp2[i].value + 60
    end
    gg.setValues(tmp2)
    --print (gg.setValues(tmp2))
    tmp4 = {}
    for v = 1, 309 do
        tmp4[v] = { address = mrrw + 0x900 +0xA0+4* v, flags = 4, value = mrrwid[v] ,name='2tmp2'..v}
     -- gg.addListItems(tmp4)  
    end
    gg.setValues(tmp4)
  --  print (gg.setValues(tmp4))
    local tmp3 = { { address = mrrw + 0xE7C, flags = 4, value = 308,name='tmp3'} }
   -- gg.setValues(tmp3)
     --gg.addListItems(tmp3)    
     local tmp5 = { { address = mrrw + 0xE80, flags = 4, value = 309,name='tmp5'} }
    gg.setValues(tmp5)
   --  gg.addListItems(tmp5)
end

function ydrw()--原地任务
    mrrwid = {}
    for i = 1, 309 do
        mrrwid[i] = i
    end
    finishites()
    
end

--随身衣柜--
KG_bzxs = true
KG_bz = true
bz_idx1 = 1
bz_idx2 = 1
KG_bjkl = {
    0,
    0,
    0,
    0,
    0,
    0,
    0
}
local zbpy_record = {}
bz_offset = { 4, 16, 12, 8, 36, 28, 20 }
function getClothes()
    if Address_clos == nil and KG_bz then
        Address_clos = searchaddr(4,"31,076",4,"-196",4,"1","0","装扮地址")
    
        KG_bz = false
    end
    if Address_clos == nil then
        gg.toast("装扮地址获取失败")
        return false
    end
    zbpy = {}
    for i = 1, 7 do
        seaio(zbpy, Address_clos + bz_offset[i], 4)
    end
    return true
end
function ssyg()--魔法菜单
  if getClothes() then
    FX = 'ssyg'
    local menu = gg.choice({
      '裤子👖','面具👓','发型🧑',
      '️斗篷🕊','背饰🎸','头饰👶🏻',
      '项链⭕','随机装扮','自动变装',
      '恢复装扮','返回上一页','返回主页'
    }, nil, '随身衣柜——自慰，别人看不见')
    if menu == 12 then Main()
     elseif menu == 11 then Main()
     elseif menu ~= nil then
      if menu >= 1 and menu <= 4 then
        bz_idx1 = menu
        ssyg_1()
       elseif menu >= 5 and menu <= 7 then
        bz_idx1 = menu
        bz_idx2 = 1
        ssyg_2()
       else
        load('A_ssyg_' .. menu .. '()')()
      end
    end
  end
end

function ssyg_1()
  FX = 'ssyg_1'
  local bz_list = {}
  for i = 1, #bz_id[bz_idx1] do
    bz_list[i] = tostring(i) .. '. ' .. bz_id[bz_idx1][i][1]
  end
  local bz_BackIdx = #bz_list + 1
  local bz_MainIdx = #bz_list + 2
  bz_list[bz_BackIdx] = '返回衣柜'
  bz_list[bz_MainIdx] = '返回主页'
  local menu = gg.choice(bz_list, {})
  if menu == bz_BackIdx then
    ssyg()
   elseif menu == bz_MainIdx then
    Main()
   elseif menu ~= nil then
    bz_idx2 = menu
    ssyg_2()
  end
end

function ssyg_2()
  FX = 'ssyg_2'
  local bz_list = {}
  for i = 2, #bz_id[bz_idx1][bz_idx2] do
    bz_list[i] = tostring(i - 1) .. '. ' .. bz_id[bz_idx1][bz_idx2][i][2]
  end
  local bz_BackIdx = #bz_list + 1
  local bz_MainIdx = #bz_list + 2
  local bz_ylgnIdx = #bz_list + 3
  bz_list[bz_BackIdx] = '返回'
  bz_list[bz_MainIdx] = '返回衣柜'
  bz_list[bz_ylgnIdx] = '返回菜单'
  local menu = gg.choice(bz_list, nil, '--想要更换成什么' .. bz_id[bz_idx1][bz_idx2][1] .. '？--')
  if menu == bz_BackIdx then
    if bz_idx1 >= 5 and bz_idx1 <= 7 then
      ssyg()
     else
      ssyg_1()
    end
   elseif menu == bz_MainIdx then ssyg()
   elseif menu == bz_ylgnIdx then Main()
   elseif menu ~= nil then
    A_ssyg(bz_id[bz_idx1][bz_idx2][menu], bz_idx1)
  end
end

function A_ssyg(Target_Item, idx)
  local ssyg = {}
  ssyg[1] = zbpy[idx]
  if KG_bjkl[idx] == 0 then
    zbpy_record[idx] = gg.getValues(ssyg)[1]
    KG_bjkl[idx] = 1
  end
  ssyg[1].value = Target_Item[1]
  ssyg[1].freeze = true
  gg.addListItems(ssyg)
  if KG_bzxs then
    gg.toast(Target_Item[2] .. '穿戴成功✓')
  end
end

function A_TGC()
  if getClothes() then
    local ssyg = {}
    ssyg[1] = zbpy[4]
    ssyg[1].value = 2219120716
    gg.setValues(ssyg)
    gg.toast('TGC蓝斗篷穿戴成功✓')
  end
end

function A_ssyg_8()
  KG_bzxs = false
  for i = 1, 4 do
    local r_type = math.random(1, #bz_id[i])
    local r_num = math.random(2, #bz_id[i][r_type])
    A_ssyg(bz_id[i][r_type][r_num], i)
  end
  for i = 5, 7 do
    local r_num2 = math.random(2, #bz_id[i][1])
    A_ssyg(bz_id[i][1][r_num2], i)
  end
  KG_bzxs = true
end

function A_ssyg_9()
  local sleep_bz = gg.prompt({'请输入变装间隔时间（默认5秒）[1,3600]'},
  {[1] = '5'},
  {[1] = 'number'})
  if sleep_bz == nil then
    return 0
   elseif sleep_bz[1] == '' then
    sleep_bz = tonumber(5)
   else
    sleep_bz = tonumber(sleep_bz[1])
  end
  gg.toast('(✧∇✧)没人比我更时尚~\n\n变装时间间隔【' .. sleep_bz .. '】秒')
  A_ssyg_8()
  local times = tonumber(0)
  while true do
    if sleep_bz <= times then
      A_ssyg_8()
      times = tonumber(0)
     else
      A_yc(1000)
      times = times + 1
    end
    if gg.isVisible(true) then
      break
    end
  end
end

function A_ssyg_10()
  gg.removeListItems(zbpy) gg.setValues(zbpy_record) gg.toast('全部装扮已恢复')
  KG_bjkl = {0,0,0,0,0,0,0}
  zbpy_record = {}
end

--魔法菜单
Kg_mf_dshh = "-〘 ❌ 〙"
Mfcw = 0
function mfxg()
  Mfpd = {}
  forseaio(1,6,Mfpd,mfdz,"-48","48",4)
  Mf_hh = {}
  seaio(Mf_hh,mfdz + 40,4,0,true)
  seaio(Mf_hh,mfdz + 0xCBC,4,6,true)--使用一个魔法后0会变
  Mf_sx = { { address = mfdz + 0xCBC, flags = 4, value = 6 } }
  Magic_list = {}
  
  for i = 1, #Magic_id do
    Magic_list[i] = tostring(i) .. ". " .. Magic_id[i][1]
  end
  
  FX = "mfxg"
  Mfpd = gg.getValues(Mfpd)
  Mfpd_txt = {}
  
  for i = 1, 6 do
  
    Mfpd_txt[i] = "空"
    
    for j = 1, #Magic_id do
      if Mfpd_txt[i]~='空' then break end
      for l = 1,#Magic_id[j][2] do
        if Mfpd[i].value == Magic_id[j][2][l][2] then
          Mfpd_txt[i] = Magic_id[j][2][l][1]
          break
        end
      end
    end
  end
  local Magic = {
    "🔮魔法1:" .. Mfpd_txt[1],
    "🔮魔法2:" .. Mfpd_txt[2],
    "🔮魔法3:" .. Mfpd_txt[3],
    "🔮魔法4:" .. Mfpd_txt[4],
    "🔮魔法5:" .. Mfpd_txt[5],
    "🔮魔法6:" .. Mfpd_txt[6],
    "电光火花(" .. Kg_mf_dshh .. ")",
    "取消全部魔法",
    "返回主页"
  }
  local menumag = gg.choice(Magic, {})
  if menumag == #Magic then
    Main()
   elseif menumag == #Magic - 1 then
    local czmg = {}
    forseaio(1,120,czmg,mfdz,"-4","4",4,0)
    gg.setValues(czmg)
    gg.toast("取消全部魔法效果")
    elseif menumag == #Magic - 2 then
    if Kg_mf_dshh == "-〘 ❌ 〙" then
      gg.addListItems(Mf_hh)
      Kg_mf_dshh = "-〘 ✅ 〙"
      gg.toast("电光火花已开启")
     else
      gg.removeListItems(Mf_hh)
      Kg_mf_dshh = "-〘 ❌ 〙"
      gg.toast("电光火花已关闭")
    end
   elseif menumag ~= nil then
::mfcw::
    Mfcw = menumag - 1
    local Magic_list={}
    for i=1,#Magic_id do
      Magic_list[i]=tostring(i)..'. '..Magic_id[i][1]
    end
    Magic_list[#Magic_list+1]='↩️'
    local menu_mf = gg.choice(Magic_list, {})
    if #Magic_list==menu_mf or menu_mf==nil then return 0 end
    local list={}
    for i=1,#Magic_id[menu_mf][2] do
      list[i]=tostring(i)..'. '..Magic_id[menu_mf][2][i][1]
    end
    list[#list+1]='↩️'
    local menu=gg.choice(list,{})
    if menu==#list then goto mfcw end
    if menu ~= nil then
      A_mfmf(Magic_id[menu_mf][2][menu][2])
    end
  end
end
function A_mfmf(idx)
    Mf_sx = {}
   seaio(Mf_sx, mfdz + 0xCBC, 4, 6, true)
    local tmp = {
        idx,
        0,
        -1600133292,
        0,
        1600132692,
        0,
        -1720562886,
        -1806973714,
        1020395176,
        131004170,
        1
    }
    Mfmf = {}
    for i = 1, 11 do
    seaio(Mfmf, mfdz + Mfcw * 48 + (i - 1) * 4, 4, tmp[i])
    end
    gg.setValues(Mfmf)
    gg.sleep(200)
    gg.addListItems(Mf_sx)
end

function banaiwuhu(sleep)--绊爱芜湖
 cui={2413103828;0;-1600133292;0;1600132692;0;-1720562886;-1806973714;1020395176;131004170;1}
 tmp={} 
 for i=1,11 do 
 tmp[i]={flags=4,address=mfdz-4+i*4,value=cui[i] } 
 end gg.setValues(tmp)
 tmpp={{flags=4,address=mfdz+0x8F4,value=6 }} 
 gg.setValues(tmpp) 
    Mf_hh = {}
    seaio(Mf_hh,mfdz + 40,4,0,true)
    seaio(Mf_hh,mfdz + 0xD78,4,6,true)
    gg.addListItems(Mf_hh)
   if sleep ~=nil then gg.sleep(sleep) end
    gg.removeListItems(Mf_hh)
gg.setVisible(false)
end

function bawhxh()--循环绊爱芜湖
 while true do
  banaiwuhu()
  gg.sleep(1500)
if gg.isVisible(true) then 
break end
  end
end

function whsm()--芜湖说明
gg.alert("随便使用一个魔法后即可生效,绊爱芜湖使用后会替换第一个魔法。")
end
--装扮菜单结束
--任务模块
function M_MRRW()
  FX = "M_MRRW"
  jiasu(1)
  local menu = gg.choice({
    "先祖任务",--1
    "光芒任务",--2
    "冥想任务",
    "植物任务",--4
    "螃蟹任务",
    "拯救任务",--6
    "冥龙任务",
    "水母任务",
    "喷泉任务",
    "季节任务",--10
    "返回主页",
  }, {})
  if menu == 8 then
    shuimu()
   elseif menu == 9 then
    wrpc()
   elseif menu == 10 then
    jjrw()
   elseif menu == 11 then
    Main()
   elseif menu ~= nil then
    RW[menu]()
  end
end

function shuimu()
  jiasu(10)
  renyimen(40)
  gg.sleep(2000)
  Teleport({235.18771362304688, 104.12296295166016, 189.17324829101562})
end


function wrpc()
  jiasu(5)
  renyimen(40)
  gg.sleep(2000)
  Teleport({138.96337890625, 0.9063517451286316, 414.215087890625})--污染喷泉坐标--pollute
end

function A_xzrw(num_map, pos_xz)
  qt(num_map)
  jiasu(10)
  Teleport(pos_xz[1])
  jiasu(9)
  gg.sleep(5000)
 -- SpiritsEnd()
  Teleport(pos_xz[2])
  gg.sleep(3000)
  jiasu(1)
  gg.toast("若先祖没反应，可以重跑先祖哦~")
end

function GQcs(i)
  qt(1)
  gg.sleep(500)
  qt(i)
end

function CatchLight(menu)
  UnlimitedEnergyStatus(true)
  gg.toast("如果失效了就重来一次哦！")
  if menu == 2 then 
  jiasu(0.001) 
  gg.sleep(800) 
  Teleport({368.9278564453125;217.63754272460938;-759.50927734375}) 
  jiasu(1)
   elseif menu == 5 then jiasu(0.001) gg.sleep(800) Teleport({94.34524536132812;227.1673583984375;186.1146697998047}) jiasu(1)
   elseif menu == 7 then jiasu(0.001) gg.sleep(800) Teleport({186.1325225830078;49.59286880493164;-488.3474426269531}) jiasu(1)
   elseif menu == 9 then jiasu(0.001) gg.sleep(800) Teleport({279.44146728516;118.86520385742;528.67883300781}) jiasu(15) gg.sleep(2500) jiasu(1)
   elseif menu == 11 then gg.sleep(1000) jiasu(0.001) gg.sleep(800) Teleport({69.35111999511719;562.9652709960938;46.71150207519531}) gg.sleep(1000) jiasu(1)
   elseif menu == 3 then jiasu(0.001) gg.sleep(1200) Teleport({-278.1680908203125;255.68118286132812;83.48990631103516}) gg.sleep(5000) jiasu(1)
   else
    if menu == 1 then jiasu(0.001) gg.sleep(800) Teleport({94.2416000366211;155.64657592773438;-19.218523025512695}) jiasu(1) end
    if menu == 4 then jiasu(0.001) gg.sleep(800) Teleport({21.184173583984375;99.25706481933594;-214.3726348876953}) jiasu(1) end
    if menu == 6 then jiasu(0.001) gg.sleep(800) Teleport({206.4205322265625;47.55751419067383;-529.426513671875}) jiasu(1) end
    if menu == 8 then jiasu(0.001) gg.sleep(800) Teleport({-10.996281623840332;9.366134643554688;189.35252380371094}) jiasu(1) end
    if menu == 10 then jiasu(0.001) gg.sleep(800) Teleport({-19.110447311401367;47.426753997802734;13.503926277160645}) jiasu(1) end
  end
  while true do
    if gg.isVisible(true) then
      break
    end
  end
  jiasu(1)
end
--任务结束

--任意传送开始
function M_rycs()
  FX = "M_rycs"
  local menu = gg.choice({
    "遇境",--1
    "晨岛",--2
    "云野",--3
    "雨林",--4
    "霞谷",--5
    "暮土",--6
    "禁阁",--7
    "暴风眼",--8
    "小王子",--9
    "其他地图",--10
    "返回主页"
  }, {})
  if menu == 1 then
    qt(menu)
  elseif menu ~= nil and menu < 11 then
local id={
{1},--1
{2,41,42,43,44,45},--2
{3,4,5,6,7,8,40},--3
{9,10,11,12,13,14,49},--4
{15,16,17,18,19,20,46,47,48},--5
{21,22,23,24,25,26,27},--6
{28,29,30,31,32},--7
{33,34,35,36,37,38,39},--8
{50,51,52,53,55,56,58,57,54,59,60},--9
{61,62,63,64,65,66,67,68},--10

}
  tmp={}
  for i = 1,#id[menu] do--菜单生成
  tmp[#tmp + 1] = {}
  tmp[#tmp] = map[id[menu][i]][3]
  end
  menu2 = gg.choice(tmp,{})
  if menu2~=nil then qt(id[menu][menu2]) end
  else
  Main()
  end
  end
  
-------------------------------任务菜单-------------------------------
  function meditation(map,position)
  qt(map)
  gg.sleep(2000)
  Teleport(position)
  jiasu(10)
  gg.sleep(1000) 
  suozishi(2)
  gg.sleep(5000) gg.toast("记得留言") jiasu(1)
end

RW={
  function ()
    local menu = gg.choice({
      "云野-蝴蝶先祖",
      "云野-挥手先祖",
      "雨林-寒冷先祖",
      "雨林-哭泣先祖",
      "霞谷-叉腰先祖",
      "墓土-害怕先祖",
      "墓土-勇敢先祖",
      "禁阁-气功先祖",
      "禁阁-站姿先祖",
      "↩️",
      "返回主页"
    }, {})
    if menu == 10 then
      M_MRRW()
     elseif menu == 11 then
      Main()
     elseif menu ~= nil then
      getFlowerAddress()
      if menu == 1 then
        A_xzrw(3, xz_yy[1][1])
       elseif menu == 2 then
        A_xzrw(4, xz_yy[4][2])
       elseif menu == 3 then
        A_xzrw(9, xz_yl[1][1])
       elseif menu == 4 then
        A_xzrw(13, xz_yl[3][3])
       elseif menu == 5 then
        A_xzrw(15, xz_xg[1][1])
       elseif menu == 6 then
        A_xzrw(22, xz_mt[1][1])
       elseif menu == 7 then
        A_xzrw(24, xz_mt[2][2])
       elseif menu == 8 then
        A_xzrw(28, xz_jg[1][2])
       elseif menu == 9 then
        A_xzrw(28, xz_jg[1][3])
      end
      FX = "M_MRRW"
    end
  end,
  function()
    local LightBall = {
      3,--云野
      2,--云野右边
      6,
      9,--雨林
      13,--雨林水母
      15,--霞谷谷
      15,--霞谷
      22,--暮土破庙
      23,--失落方舟
      28,--禁阁
      29,--禁阁隐藏图

    }
    local menu = gg.choice({
      "云野光芒",
      "青色光芒",
      "绿色光芒",
      "雨林光芒",
      "橙色光芒",
      "霞谷光芒",
      "蓝色光芒",
      "暮土光芒",
      "红色光芒️",
      "禁阁光芒",
      "紫色光芒",
     "↩️",
      "返回主页"
    }, {})
    if menu == 12 then
      M_MRRW()
     elseif menu == 13 then
      Main()
     elseif menu ~= nil then
      GQcs(LightBall[menu])
      CatchLight(menu)
      FX = "M_MRRW"
    end
  end,


  function()
    suozishi(2)
    jiasu(5)
    local menu = gg.choice({
    "蝴蝶平原的神坛",
	"幽光山洞",
	"圣岛",
	"仙乡的金塔",
	"云顶浮石",
	"云野的锦鲤池",
	"静谧庭院",
	"荧光森林",
	"雨林的神庙",
	"密林遗迹",
	"秘密花园",
	"滑冰场",
	"霞光城上层",
	"霞光城拱门",
	"落日竞技场",
	"黑水港湾的沉船",
	"巨兽荒原的神坛",
	"古战场中央",
	"边陲荒漠的神庙",
	"遗忘方舟",
	"禁阁(低层)的神坛旁",
	"禁阁(高层)的神坛旁",
	"庆典现场",
	"↩️"}, {})
    if menu == 1 then meditation(3,{94.724853515625;153.48602294921875;3.5163938999176025}) end
    if menu == 2 then meditation(5,{298.9469299316406;180.98109436035156;99.89496612548828}) end
    if menu == 3 then meditation(40,{117.38904571533203;29.085617065429688;312.6189270019531}) end
    if menu == 4 then meditation(4,{90.59362030029297;198.9470977783203;270.7969055175781}) end
    if menu == 5 then meditation(6,{-185.16073608398438;183.10426330566406;116.18496704101562}) end
    if menu == 6 then meditation(4,{103.3669662475586;251.63490295410156;472.0176696777344}) end
    if menu == 7 then meditation(9,{39.97563171386719;92.11540222167969;-231.5647430419922}) end
    if menu == 8 then meditation(10,{30.8117618560791;106.01042175292969;-74.75814819335938}) end
    if menu == 9 then meditation(14,{-12.442230224609375;107.80828094482422;81.20977020263672}) end
    if menu == 10 then meditation(13,{-1.2132474184036255;136.07029724121094;229.18789672851562}) end
    if menu == 11 then meditation(11,{-27.147045135498047;92.56639862060547;-27.503799438476562}) end
    if menu == 12 then meditation(15,{153.65658569335938;75.69300079345703;-451.5044250488281}) end
    if menu == 13 then meditation(16,{96.58367156982422;530.3274536132812;-44.80310821533203}) end
    if menu == 14 then meditation(16,{55.79777526855469;498.02862548828125;112.38156127929688}) end
    if menu == 15 then meditation(19,{85.40104675292969;138.06431579589844;-237.2593231201172}) end
    if menu == 16 then meditation(25,{-198.89434814453125;6.082498550415039;409.4452819824219}) end
    if menu == 17 then meditation(24,{99.09339141845703;74.29978942871094;-193.6372833251953}) end
    if menu == 18 then meditation(26,{-265.5046081542969;106.09679412841797;-233.43634033203125}) end
    if menu == 19 then meditation(22,{-18.469009399414062;1.204483985900879;215.5919647216797}) end
    if menu == 20 then meditation(23,{160.43292236328125;115.58052825927734;370.8262023925781}) end
    if menu == 21 then meditation(28,{-10.833337783813477;36.588096618652344;-81.43929290771484}) end
    if menu == 22 then meditation(30,{19.388391494750977;302.0858154296875;57.71057891845703}) end
    if menu == 23 then meditation(32,{13.208349227905273;62.07331085205078;-21.886953353881836}) end
  end,
  function()
    getFlowerAddress(1)
    renyimen(10)
    gg.sleep(1000)
    Teleport({
      29.493295669555664,
      106.15679931640625,
      -70.96846008300781
    })
    gg.sleep(1000)
    A_jlz()
    gg.sleep(8500)
    Teleport({
      15.686055183410645,
      106.02327728271484,
      -67.06455993652344
    })
    gg.sleep(4000)
    gg.toast("烧完了，要是没完成任务就自己动手")
  end,
  function ()
    UnlimitedEnergyStatus(true)
    renyimen(25)
    Teleport({
      -169.68191528320312,
      1.5007413625717163,
      411.57275390625
    })
    gg.toast("长按自己发出叫声，掀翻螃蟹！")
  end,
  function()
    getFlowerAddress(1)
    UnlimitedEnergyStatus(true)
    renyimen(13)
    gg.sleep(2000)
    Teleport({
      -8.70337200164795,
      134.84422302246094,
      137.0506591796875
    })
    A_jlz()
    gg.toast("正在拯救被困住的坤坤~~")
    gg.sleep(2000)
    getFlowerAddress()
  end,
  function()
    UnlimitedEnergyStatus(true)
    renyimen(24)
    gg.sleep(500)
    Teleport({
      126.38636016845703,
    73.70198822021484,
    -181.5587615966797
    })
    gg.sleep(2000)
    gg.toast("小虫子看过来！")
    jiasu(7)
    gg.sleep(2500)
    jiasu(1)
    qt(1)
  end,
}

function M_yyjj()--季节任务
  suozishi(2)
  jiasu(10)
  FX = "M_yyjj"
  local list_yyj = {
    "山谷入口",
    "向导先祖",
    "水试炼终点",
    "️土试炼终点",
    "风试炼终点",
    "火试炼终点",
    "火试炼光翼and坛",
    "返回主页"
  }
  local menu = gg.choice(list_yyj,{})
  if menu == 7 then
    hslgy()
   elseif menu == 8 then
    Main()
   elseif menu ~= nil then
    Teleport(map_yyj[menu])
    gg.toast("瞬移到→" .. list_yyj[menu])
  end
end

function M_sdjj()--小王子任务
  FX = "M_sdjj"
  local list_sdj = {
    "圣岛向导",
    "线索1",
    "线索2",
    "线索3",
    "线索4",
    "线索5",
    "线索6",
    "编钟1",
    "编钟2",
    "️编钟3",
    "编钟4",
    "编钟5",
    "编钟6",
    "返回主页"
  }
  local menu = gg.choice(list_sdj,{})
  if menu == #list_sdj then
    jjrw()
   elseif menu ~= nil then
    Teleport(map_sdj[menu])
    gg.toast("瞬移到→" .. list_sdj[menu])
  end
end

function xwz()
FX ="xwz"
local wz = {
"接受任务",
"主线1",
"主线2",
"主线3",
"主线4",
"主线5",
"主线6",
"主线7",
"返回主页"
}
local menu=gg.choice(wz,{})
if menu == 1 then
jieshou()
elseif menu == 2 then
wz1()
elseif menu == 3 then
wz2()
elseif menu == 4 then
wz3()
elseif menu == 5 then
wz4()
elseif menu == 6 then
wz5()
elseif menu == 7 then
wz6()
elseif menu == 8 then
wz7()
elseif menu == 9 then
jjrw()
end
end
function jieshou()
 qt(50) gg.sleep(1000) Teleport({133.93898010253906;12.484686851501465;347.6809997558594})
 gg.toast("请先接受任务")
 end

function wz1()--小王子任务
qt(50)
Teleport({175.51263427734375;13.599006652832031;353.0511474609375}) gg.sleep(3000) jiasu(1) gg.toast("请点击牵手") gg.sleep(3000)
jiasu(20) gg.sleep(6500) 
Teleport({204.22055053710938;8.061895370483398;432.6490478515625}) gg.sleep(5000)
Teleport({196.14614868164062;5.25846004486084;503.32855224609375}) gg.sleep(5000)
Teleport({213.0237274169922;13.97205924987793;558.094970703125}) gg.sleep(5000)
Teleport({171.92776489257812;11.667027473449707;574.3154296875}) jiasu(1)
gg.toast("请点击按键") gg.sleep(3000) jiasu(20) gg.sleep(5000)
Teleport({232.6429901123047;12.104494094848633;560.0462646484375}) jiasu(1)
gg.toast("请点击按键") gg.sleep(3000) jiasu(20) gg.sleep(3000)
Teleport({224.1492156982422;16.01643180847168;616.4157104492188}) jiasu(1)
gg.toast("请点击按键") gg.sleep(3000) jiasu(20) gg.sleep(5000)
Teleport({133.93898010253906;12.484686851501465;347.6809997558594}) jiasu(1)
gg.toast("任务完成了,提交任务吧")
end
function wz2()
qt(12) 
gg.sleep(2000)
Teleport({76.98577880859375;86.4487075805664;-258.7461853027344}) jiasu(10) gg.sleep(2000) gg.toast("请点击牵手") gg.sleep(2000) 
Teleport({61.22581100463867;111.3339614868164;-289.03875732421875}) gg.sleep(5000)
Teleport({-104.81828308105469;153.7456817626953;-291.8121032714844}) gg.toast("请点击牵手")  gg.sleep(5000)
Teleport({-107.14259338378906;204.15054321289062;-293.3249206542969}) gg.sleep(5000)
Teleport({-90.37701416015625;209.7522430419922;-290.133544921875})
gg.toast("任务完成了,提交任务吧")
end
function wz3()
qt(40) jiasu(10)
gg.sleep(2000)
Teleport({30.995647430419922;54.93016052246094;334.7182922363281}) gg.sleep(5000)
Teleport({5.30605936050415;33.68976593017578;399.56488037109375}) gg.sleep(5000)
Teleport({63.40259552001953;32.300148010253906;375.7768249511719}) gg.sleep(5000)
Teleport({85.51576232910156;28.868852615356445;323.8835754394531}) gg.sleep(5000)
Teleport({-42.11030578613281;0.44160813093185425;365.1759338378906}) gg.sleep(5000)
Teleport({53.98514175415039;102.78278350830078;300.1388854980469}) gg.sleep(5000)
gg.toast("任务完成了,提交任务吧")
end
function wz4()
qt(50)
jiasu(10)
Teleport({203.53994750976562;11.347504615783691;535.029052734375}) gg.sleep(5000)
LightAFire() gg.sleep(5000)
Teleport({215.0520477294922;13.925033569335938;558.2158813476562}) gg.sleep(5000)
Teleport({231.9755096435547;12.277155876159668;561.66796875}) gg.sleep(5000)
Teleport({207.2823486328125;12.423746109008789;579.4335327148438}) gg.sleep(5000)
Teleport({178.2588653564453;11.44039249420166;571.4818115234375}) gg.sleep(5000)
Teleport({228.0545196533203;15.05758285522461;590.9579467773438}) gg.sleep(5000)
Teleport({195.27403259277344;12.649223327636719;557.0174560546875}) gg.sleep(5000)
Teleport({237.5091552734375;15.996828079223633;602.8434448242188}) gg.sleep(5000)
Teleport({228.10931396484375;16.635719299316406;605.49755859375}) gg.sleep(5000)
gg.toast("任务完成了,提交任务吧")
end

function wz5()
qt(47)
gg.sleep(2000)
jiasu(10)
Teleport({-359.204345703125;257.1060791015625;202.27972412109375}) 
gg.toast("弹琴谈俩个乐曲 也可以不谈 任务完成")
end
function wz6()
qt(50) jiasu(10)
gg.sleep(2000)
Teleport({584.8915405273438;54.17000961303711;-80.54927062988281}) gg.sleep(5000)
Teleport({526.142333984375;60.88623809814453;-18.68052864074707}) gg.sleep(5000)
Teleport({444.55859375;61.836822509765625;143.34251403808594}) gg.toast("点火") gg.sleep(10000)
Teleport({396.1453857421875;57.23339080810547;176.04408264160156}) gg.sleep(5000)
Teleport({375.4035949707031;57.93336486816406;211.40716552734375}) gg.sleep(5000)
end
function wz7()
qt(38)
jiasu(10)
gg.sleep(2000)
Teleport({1.401298464324817E-45;1.401298464324817E-45;1.0171452760696411})
end
--结束王子季任务


function M_mxjj()
  FX = "M_mxjj"
  local list_mxj = {
    "梦想向导",
    "任务1",
    "任务2",
    "任务3",
    "任务4",
    "任务5",
    "返回主页"
  }
  local menu = gg.choice(list_mxj,{})
  if menu == #list_mxj then
    jjrw()
   elseif menu ~= nil then
    qt(map_mxj[menu+6])
    gg.sleep(1000)
    Teleport(map_mxj[menu])
    gg.toast("瞬移到→" .. list_mxj[menu])
    if menu>1 and menu~=6 then
      getFlowerAddress()
      for i=1,10 do
        gg.sleep(3000)
        A_LightChip()
      end
    end
  end
end
function jjrw()--季节任务
  FX = "jjrw"
  local list= {
    {"魔法季光球","RW[2]"},
    {"圣岛季瞬移","M_sdjj"},
    {"预言季试炼","M_yyjj"},
    {"梦想季瞬移","M_mxjj"},
	   {"王子季瞬移","xwz"},
    {"返回主页","Main"}
  }
  jkmmchoice(list)
end

function ydzx()--原地季节任务
     gg.clearResults()
	 gg.setRanges(4|-2080896)
	 search("7037807",4)
	 gg.getResults(9999)
	 gg.editAll("0",4)
	 gg.clearResults()
  gg.toast("任务已完成")
end
--任务结束

-----------------------------光翼菜单---------------------------------
function PTGY(Num_GY)
  local Tab_GY = gg.getValues(LightCount)
  Num_Xggy = Tab_GY[1].value
  LightCount[1].value = Num_GY
  gg.setValues(LightCount)
end

function xiguangyi()---进图吸翼
local a1=gg.alert("是否要使用进图吸翼?光翼为高风险功能。任何使用不当,后果自负,请不要造谣！","是","否")
  if a1 == 2 then gy() end
  bin=gg.prompt({"🕰吸光翼间隔[15;60]","随机附加时间[0;10]",xichenaa},
  {30,5,""},
  {'number','number','text'})

  if bin~=nil then
    if bin[3]~=nil then gg.toast("error") return end
    for i = 2, 49 do
      if map[i][5] == 1 then
        qt(i)
        gg.sleep(500)
        local x = {}
        tmp = gg.getValues(LightChild)
        for i, v in ipairs(tmp) do
          if v.value == 1 then
            x[#x + 1] = {}
            x[#x].address = tmp[i].address
          end
        end
        gg.toast("检测当前地图未拾取光翼数量为:["..#x.."]")
        gg.sleep(2000)
        for i = 1, #x do
          gg.setValues({{address=x[i].address,flags = 4,value = 4}})
          jiasu(15)
          gg.sleep(200)
          jiasu(5)
          gg.setValues({{address=x[i].address,flags = 4,value = 8}})
          jiasu(1)
          local T=math.random(0,bin[2])+bin[1]
          local k=0
          while true do
            gg.sleep(1000)
            k=k+1
            gg.toast("等待"..(T-k).."秒后吸下一个光翼\n当前地图剩余:["..(#x-i).."]个光翼")
            if k == T then
              break
            end
          end
        end
      end
    end
  end
   end
   
function ydgy()--原地光翼控制
local a1=gg.alert("原地光翼为必封功能。是否要使用原地光翼?我要是你就不用。任何使用不当,后果自负,请不要造谣！","是","否")
  if a1 == 2 then gy() end
  m = gg.prompt({"自定义光翼获取速度(单位:毫秒/ms)"}, {[1] = ""}, {[1] = "number"})
  if m == nil then gy() end
  ydgy1()
end
function ydxzy()
jiasu(50) ydgyb() gg.toast('永久光翼收集完成') jiasu(1) end
function yddty()
jiasu(50) ydgya() gg.toast('地图光翼收集完成') jiasu(1) end
function ydcsy()
jiasu(50) ydgycs() gg.toast('测试光翼收集完成') jiasu(1) end

function ydgy2()
jiasu(50) ydgya() ydgyb() gg.toast('光翼收集完成') jiasu(1)
end

function ydgycs()
for p = 1, #csyid do
Switch = {{address = ydgypy,flags = 4,value = 257}};
gg.setValues(Switch)
gg.toast(' ' .. p .. '/' .. #csyid .. '')
local Light = {}
for i = 1, 28 do
qwq = '.' .. csyid[p][1]
Light[i]={address=ydgypy + 7 + i,flags=1,value=qwq:byte(i) or 0}
Switch1 = {{address = ydgypy,flags = 4,value = 257}}
Switch2 = {{address = ydgypy+0x80,flags = 4,value = 65793}}
Switch3 = {{address = ydgypy+0x58,flags = 4,value = 5}} end gg.setValues(Light);gg.setValues(Switch1);gg.setValues(Switch2);gg.setValues(Switch3);gg.sleep(50)  end
Switch[1].value = 1;gg.setValues(Switch);gg.clearResults();gg.toast('永久光翼收集完成')
end

function ydgya()
for p = 1, #dituyiid do
Switch = {{address = ydgypy,flags = 4,value = 257}};
gg.setValues(Switch)
gg.toast(' ' .. p .. '/' .. #dituyiid .. '')
local Light = {}
for i = 1, 28 do
qwq = '.' .. dituyiid[p][1]
Light[i]={address=ydgypy + 7 + i,flags=1,value=qwq:byte(i) or 0}
Switch1 = {{address = ydgypy,flags = 4,value = 257}}
Switch2 = {{address = ydgypy+0x80,flags = 4,value = 65793}}
Switch3 = {{address = ydgypy+0x58,flags = 4,value = 5}} end
gg.setValues(Light);--gg.addListItems(Light)
gg.setValues(Switch1);--gg.addListItems(Switch1)
gg.setValues(Switch2);--gg.addListItems(Switch2)
gg.setValues(Switch3);--gg.addListItems(Switch3)
gg.sleep(50) end Switch[1].value = 1;gg.setValues(Switch);gg.clearResults();gg.toast('地图光翼收集完成') end

function ydgyb()
for p = 1, #yongjiuyiid do
Switch = {{address = ydgypy,flags = 4,value = 257}};
gg.setValues(Switch)
gg.toast(' ' .. p .. '/' .. #yongjiuyiid .. '')
local Light = {}
for i = 1, 28 do
qwq = '.' .. yongjiuyiid[p][1]
Light[i]={address=ydgypy + 7 + i,flags=1,value=qwq:byte(i) or 0}
Switch1 = {{address = ydgypy,flags = 4,value = 257}}
Switch2 = {{address = ydgypy+0x80,flags = 4,value = 65793}}
Switch3 = {{address = ydgypy+0x58,flags = 4,value = 5}} end gg.setValues(Light);gg.setValues(Switch1);gg.setValues(Switch2);gg.setValues(Switch3);gg.sleep(50)  end
Switch[1].value = 1;gg.setValues(Switch);gg.clearResults();gg.toast('永久光翼收集完成')
end



function ydgy1()--原地光翼

  jiasu(50)
  Light={}
  Light[1] = {address = ydgypy ;flags =4} --光翼257:a:65793::140当无翼时a等于1，有翼时为6
for p = 1, #wipeid do
Switch = {{address = ydgypy,flags = 4,value = 257}};
gg.setValues(Switch)
gg.addListItems(Switch)
gg.toast(' ' .. p .. '/' .. #wipeid .. '')
local Light = {}
for i = 1, 28 do
qwq = '.' .. wipeid[p][1]
Light[i]={address=ydgypy + 7 + i,flags=1,value=qwq:byte(i) or 0}
Switch1 = {{address = ydgypy,flags = 4,value = 257}}
Switch2 = {{address = ydgypy+0x80,flags = 4,value = 65793}}
Switch3 = {{address = ydgypy+0x58,flags = 4,value = 5}}
     end
        gg.setValues(Light);gg.setValues(Switch1);gg.setValues(Switch2);gg.setValues(Switch3);gg.sleep(50)
    end
    Switch[1].value = 1;gg.setValues(Switch);gg.clearResults();gg.toast('永久光翼收集完成')

    rnew = {
        {
            address = Light[1].address + 7+214,
            flags = 1,
            name = '未知光翼',
        },

        }
gg.addListItems(rnew)
  
end

function JRJG()--瞬移金人间隔
  qqq=gg.prompt({"金人瞬移间隔(默认60s)","\n过图时间(默认10s)"},
  {JRtime,GTTIME},
  {'number','number'})
  if qqq~= nil then
    JRtime=qqq[1]
    GTTIME=qqq[2]
    gg.toast("瞬移金人间隔："..JRtime.."ms 过图间隔："..GTTIME.."ms ")
  end
end

function PTsmall(ptmap,pd)
    if pd~=X then 
    qt(pd)
    gg.sleep(GTTIME)
     end
    for i = 1, #ptmap do
      Teleport(ptmap[i])
      gg.toast("瞬移"..map[pd][3].."光翼 [" .. i .. "] 完成")
      gg.sleep(JRtime)
    end
    --gg.sleep(1000)
    gg.toast(""..map[pd][3].."结束")
end

function sygy()--瞬移光翼
local a1=gg.alert("瞬移光翼有封号风险。是否要使用瞬移光翼?我要是你就不用。任何使用不当,后果自负,请不要造谣！","是","否")
  if a1 == 2 then gy() end
JRJG()
for i=1,#JRtable do
for j=1,#JRtable[i] do
PTsmall(JRtable[i][j][1],JRtable[i][j][2])
end
end
end
--结束
function zhayicd()--炸翼修改
  local bin=gg.prompt({"🌞祝你天天开心[0;30]"},
  {0},
  {"number"})
  if bin == nil then
    return 0
   else
    bin = tonumber(bin[1])
  end
  Lightboom[1].value = bin
  gg.setValues(Lightboom)
end



wykg="-〘 ❌ 〙"--无翼
function wuyi()--无翼
  local senergy = {} 
  seaio(senergy,dpaddr,16,0,true)
  if wykg=="-〘 ❌ 〙" then 
  senergy[1].value = "0" 
  gg.addListItems(senergy) 
  gg.toast("无翼已开启") 
  wykg="-〘 ✅ 〙"
   else senergy[1].value = "1"
   gg.addListItems(senergy) 
   gg.toast("无翼已关闭")
   wykg="-〘 ❌ 〙" end
end

function xggy()--修改光翼
  local tmp = gg.getValues(LightCount)
  Num_xggy = tmp[1].value
  local num_GY = gg.prompt({
    "请输入光翼的数量[0-300]"
  }, {
    [1] = Num_xggy
  }, {
    [1] = "number"
  }
  )
  if num_GY == nil or num_GY[1] =="" then
    return 0
   else
    num_GY = tonumber(num_GY[1])
  end
  LightCount[1].value = num_GY
  gg.setValues(LightCount)
end
--光翼菜单结束

---------------------------------献祭菜单---------------------------------
--献祭模块
function dlxjdy()--独狼献祭调用
    gg.toast('开始自动献祭')
    gg.sleep(1000)
    send_stars_val = { { address = xjdiaoxiang, flags = 4, value = 2, freeze = true } }
    gg.addListItems(send_stars_val)
    tmp = gg.getValues(LightCount)
    repeat
        gg.sleep(500)
        tmp = gg.getValues(LightCount)
    until tmp[1].value == 0
    send_stars_val[1].freeze = false
    gg.addListItems(send_stars_val)
end

--自定义次数献祭
function A_ydxj()
    local x = gg.prompt({ '献祭次数' }, { [1] = 1 }, { [1] = 'number' })
    if x == nil then
        return 0
    else
        x = tonumber(x[1])
    end
    for i = 1, x do
        qt(35)
        jiasu(20)
        gg.sleep(500)
        dlxjdy()
        gg.sleep(5000)
        qt(38)
        jiasu(20)
        gg.sleep(5000)
        gg.toast('完成')
    end
end
--结束


function xjcy()--献祭常用
    FX = "xjcy"
    menu = gg.choice({
        "传送到暴风眼",
        "传送一图终点",
        "传送二图终点",
        "直接传送伊旬",
        "结束献祭动画",
        "不玩了我要回家🥺",
        "↩️"
    }, {} )
    if menu == 1 then
        Teleport({ -25.471393585205078, 0.34619253873825073, -14.354535102844238 })
    end
    if menu == 2 then
    Teleport({ -0.42702335119247437, 196.06117248535156, -20.18721580505371 }) end
    if menu == 3 then
    gg.toast("快拿小金人")
    Teleport({ 2.020233154296875, 262.186767578125, -235.93716430664062 })
    gg.sleep(5000)
    Teleport({ 6.777451992034912, 265.9830627441406, -243.30487060546875 }) end
    if menu == 4 then renyimen(35) end
    if menu == 5 then renyimen(39);renyimen(1) end
    if menu == 6 then renyimen(1) end
    if menu == 7 then xj() end
end

function slcyid1()--水试炼终点
slcyid1_1=gg.choice({
          "第一坨烛火",
          "第二坨烛火",
          "𝘉𝘢𝘤𝘬"},{})
if slcyid1_1==1 then 
qt(42)
Teleport({36.726173400878906;65.56058502197266;-99.7840805053711})
end
if slcyid1_1==2 then
qt(42)
Teleport({-0.6197408437728882;69.88878631591797;-429.2400207519531})
 end
end

function slcyid2()--土试炼终点
qt(43)
Teleport({-13.375536918640137;133.8769073486328;3.4706342220306396})
end

function slcyid3()--风试炼终点
qt(44)
Teleport({-6.532476425170898;104.790771484375;-131.01976013183594})
end

function slcyid4()--火试炼终点
qt(45)
UnlimitedEnergyStatus()
Teleport({-14.752881050109863;50.1752815246582;-249.505615234375})
end

function nsyl()--拿剩余蜡
  renyimen(38)
  jiasu(20)
  gg.toast("四秒后自动传送")
  gg.sleep(5000)
  renyimen(39)
  renyimen(2)
  gg.sleep(3000)
  renyimen(1)
  jiasu(1)
  gg.clearResults()
gg.clearList()
end
--自定义拿剩余蜡烛次数
function A_Nalazu()
    local x = gg.prompt({ '拿蜡烛次数' }, { [1] = 1 }, { [1] = 'number' })
    if x == nil then
        return 0
    else
        x = tonumber(x[1])
    end
    for i = 1, x do

        gg.sleep(1000)
        nsyl()
        gg.sleep(1000)
        
        
       
        gg.toast('完成')
    end
end
--结束
function xianji()--独狼献祭
jiasu(15)
renyimen(35)
gg.sleep(2000)
dlxjdy()
gg.sleep(5000)
renyimen(38)
gg.sleep(7000)
renyimen(39)
renyimen(2)
renyimen(1)
jiasu(1)
gg.clearResults()
gg.clearList()
end

--结束献祭 


function ydxz()--一键先祖
for i=1,43 do
seaio(fsxz,yjxzaddra+0x30*i-0x30,32,yjxzs[i],true)
end
seaio(fsxz,yjxzaddrb,4,46,true)
gg.addListItems(fsxz)
end

function ydfks()--一键复刻先祖
qt(9)
gg.sleep(2000)
for i=1,43 do
seaio(fsxz,yjxzaddra+0x30*i-0x30,32,yjfks[i],true)
end
seaio(fsxz,yjxzaddrb,4,46,true)
gg.addListItems(fsxz)
gg.sleep(500)
qt(1)
gg.sleep(500)
Teleport({8.632582664489746;0.7702206969261169;-8.982224464416504})
end
----开先祖菜单
function kaixianzuMain()
  FX = "kaixianzuMain"
  if kg==0 then
    gg.setVisible(false)
    gg.clearResults()
    gg.setRanges(4|-2080896)
    search("414084241" ,gg.TYPE_QWORD)
    resultCount = gg.getResultCount()
    if resultCount < 8 then
      gg.toast("开先祖获取失败,启动备用模式")
      bykxz = tonumber("0x61104")----遇境先祖
      if bykxz~= nil then kg = 1 gg.alert("开启成功") else gg.toast("获取失败") Main() end
     else
      kg = 1
      result = gg.getResults(resultCount)
      
    end
  end
  menu=gg.choice({
    "基础先祖",
    "复刻先祖(只能开当前复刻的先祖,否则断线)",
    "飞行季先祖",
    "恢复",
    "上一页"
  }, {})
  if menu == 1 then kxz(xianzu)
   elseif menu == 2 then kxz(xzfk)
   elseif menu == 3 then kxz(mxxianzu)
   elseif menu == 4 then
    i=1
    if bykxz~= nil then gg.setValues({{address =bykxz, flags = 32, value = xianzu[i][1]}})
     else
      gg.setValues({{address =result[2].address, flags = 32, value = xixianzuaddr[i][1]}})
      gg.setValues({{address =result[3].address, flags = 32, value = xianzu[i][1]}})
      gg.setValues({{address =result[8].address, flags = 32, value = xianzu[i][1]}})
      gg.setValues({{address =result[#result].address, flags = 32, value = xianzu[i][1]}})
    end
   elseif menu == 5 then Main() end
end
function gguipd()
::ks::
  while true do
    if gg.isVisible(true) then
      gg.setVisible(false)
      break return
    end
    gg.sleep(800)
  end
end
function kxz(xianzu)
  tmp={}
  for k,v in pairs(xianzu)do
    tmp[#tmp + 1] = {}
    tmp[#tmp] = xianzu[k][2]
  end
  local menu_pt = gg.multiChoice(tmp,{}, "-----请选择你要解锁的先祖\n务必解锁(晨岛)伸手先祖-----")
  gg.toast("点击gg开始")
  if menu_pt[1] then
    for k,v in pairs(xianzu)do
::ks::
      gguipd()
      i=k
      menu=gg.choice({
        "下一个",
        "退出"
      },{})
      if menu == 2 then Main()
       elseif menu~=1 then goto ks end
      if bykxz~= nil then gg.setValues({{address =bykxz, flags = 32, value = xixianzuaddr[i][1]}})
       else
        gg.setValues({{address =result[2].address, flags = 32, value = xixianzuaddr[i][1]}})

        gg.setValues({{address =result[3].address, flags = 32, value = xixianzuaddr[i][1]}})
        gg.setValues({{address =result[8].address, flags = 32, value = xixianzuaddr[i][1]}})
        gg.setValues({{address =result[#result].address, flags = 32, value = xixianzuaddr[i][1]}})
      end
    end
   else
    for k,v in pairs(xianzu)do
      if menu_pt[k] then
::ks::
        gguipd()
        i=k
        menu=gg.choice({
          "下一个",
          "退出"
        },{})
        if menu == 2 then Main()
         elseif menu~=1 then goto ks end
        if bykxz~= nil then gg.setValues({{address =bykxz, flags = 32, value = xianzu[i][1]}})
         else
         
          gg.setValues({{address =result[2].address, flags = 32, value = xianzu[i][1]}})
          gg.setValues({{address =result[3].address, flags = 32, value = xixianzuaddr[i][1]}})
          gg.setValues({{address =result[8].address, flags = 32, value = xixianzuaddr[i][1]}})
          gg.setValues({{address =result[#result].address, flags = 32, value = xixianzuaddr[i][1]}})
        end
      end
    end
  end
end
---结束开先祖菜单

-------------------------景点菜单模块----------------------
function Z_enjoyCoor(x)--共享景点
    gxzb='http://cloud.tonwzf.xyz/api/v3/file/get/2411/%E6%99%AF%E7%82%B9%E6%95%B0%E7%BB%84.lua?sign=dDUGag79mjpIYs2cL_NhK1nk312WWwTapG0LTI2NEww%3D%3A0'
pcall(load(gg.makeRequest(gxzb).content))
    if gxzb == nil then
    gg.alert("坐标数据获取失败，请稍后再试")
    jd() end
    ---载入云端坐标
    ydzb()
    ---初始化载入的数组
    tmpName = {} ---接收名称
    tmpId = {} ---接收地图ID
    tmpCoor = {} ---接收坐标
    for exp = 1, #zbid do
        tmpName[exp] = zbid[exp][1]
        tmpId[exp] = zbid[exp][2]
        tmpCoor[exp] = zbid[exp][3]
    end
    menu = gg.choice(tmpName, {})
    if menu ~= nil then
        menu2 = gg.alert("是否传送该景点：\n\t传送地图：" .. map[tmpId[menu]][3], "传送", "返回")
        if menu2 == 1 then
            renyimen(tmpId[menu])
            if drcf == true then
                gg.toast("12秒后开始瞬移")
                gg.sleep(8000)
            end
            gg.sleep(4000)
            Teleport(tmpCoor[menu])
            gg.isVisible(false)
            else jd() end
            else jd() end
            end

function jdcd()--景点彩蛋
  FX='jdcd'
  local menu = gg.choice({
    "遇境",--1
    "晨岛",--2
    "云野",--3
    "雨林",--4
    "霞谷",--5
    "暮土",--6
    "禁阁",--7
    "失色之地",--8
    "重生之路",--9
   	"飞行季地图",--10
    "返回主页"--11
  }, {}, "当前地图为:"..map[X][3].."")
  if menu == 11 then Main()
   else
    tmp={} 
	for i = 1,#Map_cd[menu] do
		tmp[#tmp + 1] = {}
		tmp[#tmp] = Map_cd[menu][i][2] --菜单生成
	end
		local menu2=gg.choice(tmp,{})
    if menu2 then 
		qt(Map_cd[menu][menu2][1][4])
		gg.sleep(2000)
		Teleport(Map_cd[menu][menu2][1]) 
			end
		end
	end

function scjd()--上传景点
    wzpd()
    local weizhi = gg.getValues(dqwzaddr)
    local dtid=weizhi[1].value
    local xzy = A_Get_zero()
    local zuobiao = "" .. string.format("%.f", xzy[1]) .. ";" .. string.format("%.f", xzy[2]) .. ";" .. string.format("%.f", xzy[3]) .. ""
    local positionPrT = gg.prompt(
            { "当前地图：" .. map[X][3] .. "\n当前坐标：" .. zuobiao .. "\n请输入景点名字:"},
            { [1] = "" },
            { [1] = "text" })


    if positionPrT == nil then return 0 end
    if positionPrT[1] == nil or #positionPrT[1] == 0 then 
        jdzcd()
    else
sclj="http://yx.tangdouz.com/yx.php?to=3029534547@qq.com&nr="..positionPrT[1]..","..dtid..",".. zuobiao.."&zt="..positionPrT[1]..","..X..",".. zuobiao..""

local csgg = gg.makeRequest(sclj).content
if csgg == "发送成功" then
local loading = getLoadingBox(csgg)
loading['显示']()
gg.sleep(2000)
loading['关闭']()
Main() else
local loading = getLoadingBox("上传失败，错误信息："..csgg"")
loading['显示']()
gg.sleep(2000)
loading['关闭']()
Main()
end
end
end

function fzzb()--复制坐标
     local xzy = A_Get_zero()
    gg.copyText("{" .. xzy[1] .. ";" .. xzy[2] .. "; " .. xzy[3] .. "}")
end

function syzb()--瞬移坐标
  local xzy = A_Get_zero()
  local positionPrT = gg.prompt({"请输入坐标格式{X,Z,Y}"},{""},{"text"})
  if(positionPrT == nil or 
  #positionPrT == 0) then
    gg.toast("未输入坐标")
   else
    Teleport(assert(load("return " .. positionPrT[1]))())
    gg.toast("瞬移坐标完成")
  end
end

--景点菜单结束

-----------------------------新号菜单---------------------------------
function xhkqm()--新号开七门
	  renyimen(31)
    gg.sleep(500)
    jiasu(10)
    gg.setVisible(false)
    gg.sleep(14500)
    Teleport({9.837,327.414,13.489})
    gg.toast("请在5s内进门")
    jiasu(1)
    gg.sleep(8500)
    Teleport({1.292,0.341,4.917})
    suozishi(2)
    jiasu(10)
    gg.sleep(4000)
    Teleport({9.837,327.414,13.489})
    gg.toast("请再次进入门")
    gg.addListItems({{address=zspy,flags=4,value=2,freeze=false}})
    jiasu(1)
    gg.sleep(2500)
    jiasu(10)
    gg.sleep(6000)
    jiasu(1)
end

function xhkxz()--一键先祖
for i=1,43 do
seaio(fsxz,yjxzaddra+0x30*i-0x30,32,yjxzs[i],true)
end
seaio(fsxz,yjxzaddrb,4,46,true)
gg.addListItems(fsxz)
end

--新号菜单结束

-------------------------强制菜单----------------------
function dzhd(fusheng)--强制动作
tmp={}
for i=1,8 do
seaio(tmp,qzdz+(i-1)*0x10C10,4,fusheng,true)
seaio(tmp,qzdz+4+(i-1)*0x10C10,4,41249,true)
end
gg.setValues(tmp)
gg.addListItems(tmp)
end
function qthddz()--全体互动动作
dz=gg.choice({"1 牵手","2 击掌","3 拥抱一级","4 击掌二级","5 碰拳一级","6 双击掌一级","7 奇怪动作","8 深情拥抱","9 拥抱二级","10 击掌二级","11 碰拳二级","12 双击掌二级","13 背背一级","14 背背二级","15 摸头一级","16 摸头二级","17 打闹一级","18 打闹一级","19 熊抱一级","20 熊抱二级"},{})
    if dz == nil then
        Main()
    else
        dzhd(dz)
    end
end

xhkg = "-〘 ❌ 〙"
function xhms()--小黑模式
  local tempData = {}
  seaio(tempData,wxnladdr[1].address,16,"-99")
  if xhkg == "-〘 ❌ 〙" then 
  tempData[1].freeze = true 
  gg.addListItems(tempData) 
  xhkg = "-〘 ✅ 〙"
  else tempData[1].freeze = false 
  gg.addListItems(tempData)
  gg.removeListItems(tempData)
  xhkg = "-〘 ❌ 〙" end
end

function qcsywjxg()--清除所有玩家效果效果
gg.clearList()
end  
--强制菜单结束

-----------------------PHP+lua聊天室------------------------
local ltwz = "http://guci.hackersafe.cn/gyjb/" 
function jklts()---- 聊天室
FX="jklts"
local bc = io.open("/sdcard/gy_lts")
if bc == nil then
io.open("/sdcard/gy_lts", "w"):write("【账号】野外中出先生【账号】\n【表情】ᥬ😂᭄【表情】"):close()
end
du = io.open("/sdcard/gy_lts","r"):read("*a")
zh = du:match("【账号】(.-)【账号】")
bq = du:match("【表情】(.-)【表情】")
Sa = gg.choice({"账号信息","进入聊天室","返回主页"},{},"当前名字:"..zh.."  表情:"..bq.."")
if Sa == 1 then ltsz()
elseif Sa == 2 then lts()
elseif Sa == 3 then Main()
end
end

function ltsz()----聊天设置
dl=gg.prompt({"聊天名字","表情头像","确定更换"},{zh,bq,true},{"text","text","checkbox"})
if dl == nil then jklts() end
if dl[3]==true then
zh = dl[1]
bq = dl[2]
io.open("/sdcard/gy_lts", "w"):write("【账号】" .. zh .. "【账号】\n【表情】" .. bq .. "【表情】"):close() end
end

function lts()----聊天室
jbmz="-[ 脚本]-"
local lt = ltwz.."feedback.txt"
local wb = gg.makeRequest(lt).content
fsnr=gg.prompt({"光遇脚本聊天室\n——————————————————————————\n"..wb},nil,{"text"})
if fsnr == nil then jklts() else
fsnrlj=ltwz.."send.php?title="..jbmz..zh.."&content="..fsnr[1].."&tx="..bq
local fsnr = gg.makeRequest(fsnrlj).content
lts()
end
end
--聊天室结束

--[[
function cxyq()--查询疫情
gg.setVisible(false)
yq=gg.prompt({"输入你想查询的地区"},{""},{"text"})
YQ="https://www.wigwy.xyz/api/yiqing?city="..yq[1]..""
YQ1=gg.makeRequest(YQ).content
gg.alert(YQ1)
end
]]

----------自动弹琴
zdtqkg="未授权"
function zdtqpz()--自动弹琴配置
if zdtqkg=="未授权" then
local loading = getLoadingBox('正在检测无障碍权限,若没有开启请开启后使用...')
loading['显示']()
gg.sleep(3000)
loading['关闭']()
gg.setVisible(false)
assert(auto.start())
zdtqkg="已授权"
else assert(auto.start())
zdtqkg="已授权"
gg.toast("正在获取云端")
end
end

function zdtq()--自动弹琴
zdtqpz()
QP="http://cloud.tonwzf.xyz/api/v3/file/get/2413/%E8%87%AA%E5%8A%A8%E5%BC%B9%E7%90%B4.lua?sign=e3kuNVgD58-EnDnc7FhY4bP0Q9_Y-3cVrk7yHGAZZUE%3D%3A0"
QP1=gg.makeRequest(QP).content
QP2=QP1:match("【琴谱】(.-)【琴谱】")
pcall(load(gg.makeRequest(QP2).content))
end
--------自动弹琴结束

function ydyg()
local  fs = {--发饰
         [1]={address = ydygaddr , flags = 4 , value = 1},
         [2]={address = ydygaddr + 0x40 , flags = 4 , value = 2},
         [3]={address = ydygaddr + 0x3C , flags = 4 , value = 2},
             }
local  dp = {--斗篷
         [1]={address = ydygaddr , flags = 4 , value = 1},
         [2]={address = ydygaddr + 0x40 , flags = 4 , value = 2},
         [3]={address = ydygaddr + 0x3C , flags = 4 , value = 1},
             }
local  mj = {--面具
         [1]={address = ydygaddr , flags = 4 , value = 1},
         [2]={address = ydygaddr + 0x40 , flags = 4 , value = 2},
         [3]={address = ydygaddr + 0x3C , flags = 4 , value = 3},
             }
local  kz = {--裤子
         [1]={address = ydygaddr , flags = 4 , value = 1},
         [2]={address = ydygaddr + 0x40 , flags = 4 , value = 2},
         [3]={address = ydygaddr + 0x3C , flags = 4 , value = 0},
             }
local  ts = {--头饰
         [1]={address = ydygaddr , flags = 4 , value = 1},
         [2]={address = ydygaddr + 0x40 , flags = 4 , value = 2},
         [3]={address = ydygaddr + 0x3C , flags = 4 , value = 6},
             }
local  lj = {--领结
         [1]={address = ydygaddr , flags = 4 , value = 1},
         [2]={address = ydygaddr + 0x40 , flags = 4 , value = 2},
         [3]={address = ydygaddr + 0x3C , flags = 4 , value = 4},
             }
local  bs = {--背饰
         [1]={address = ydygaddr , flags = 4 , value = 1},
         [2]={address = ydygaddr + 0x40 , flags = 4 , value = 2},
         [3]={address = ydygaddr + 0x3C , flags = 4 , value = 8},
             }

HG=gg.choice({
          "发饰衣柜",
          "斗篷衣柜",
          "面具衣柜",
          "裤子衣柜",
          "头饰衣柜",
          "领结衣柜",
          "背饰衣柜",
          "返回主页"
          },{})
if HG == 1 then gg.setValues(fs)  end
if HG==2 then gg.setValues(dp) end
if HG==3 then gg.setValues(mj) end
if HG==4 then gg.setValues(kz) end
if HG==5 then gg.setValues(ts) end
if HG==6 then gg.setValues(lj) end
if HG==7 then gg.setValues(bs) end
if HG==8 then Main() end
end


function yhfk()--用户反馈
email=gg.prompt({"用户反馈：\n功能问题或者需要优化","方便作者联系，请输入你的联系方式"},{""},{"text"})
if email== nil then return 0 end
if email[1]=="" or email[2] =="" then 
gg.alert("有选项未输入") else
yxfk="http://yx.tangdouz.com/yx.php?to=3029534547@qq.com&nr=【问题】："..email[1].."&zt=【反馈者】："..email[2]..""
yxfk1=gg.makeRequest(yxfk).content
local loading = getLoadingBox("已送达，感谢您的反馈……")
loading['显示']()
gg.sleep(3000)
loading['关闭']() end
end

--退出辅助
function Exit()
gg.clearResults()
gg.clearList()
tcjk=gg.alert("是否退出 ?","是","否")
if tcjk == 1 then os.exit() end
if tcjk == 2 then Main() end
end
-----------------------------分菜单---------------------------------
function cdsx()
         wzpd()
 
  ptzcd={--跑图子菜单
         {"原地跑图(稳定)","ydpt"},
         {"半自动跑图(稳如狗)","bzdpt"},
         {"半自动跑图(自动)","xbzdpt"},
         {" 跑图[养小号](稳定)","jkpt"},
         {"线性跑图","xxpt"},
         {"全自动跑图","qzdpt"},
         {"设置跑图间隔","PTSZ"},
         {"霞谷蜡烛","xglz"},
         {"返回主页","Main"}
         }
  cyzcd={--常用子菜单
         {"无限能量("..wxnlkg..")","UnlimitedEnergyStatus"},
         --{"无限氧气("..wxyqkg..")","yangqi"},
         --{"聊天窥屏("..kpkg..")","ltkp"},
         --{"新聊天窥屏("..HB..")","ltkp1"},
         {"获取潜水功能","hqqsgn"},
         {"录制影像","luzhilazhu"},
         {"修改画质","xghz"},
         {"加强跳跃","qhty"},
         {"查询身高","cxsg"},
         {"拨云见日","byjr"},
         {"去除风墙","qcfq"},
         {"自动点蜡烛("..xadlzkg..")","xadl"},
         {"魔法商店","mfsd"},
         {"无限烟花","wxyh"},
         {"隐形钢琴[和谐]","yxgq"},
         {"一键点炸吸显","yijian"},
         {"显示隐藏蜡烛","xianlazhuk"},
         {"全图点火","LightAFire"},
         {"全图吸火","absorbCandlelight"},
         {"全图炸花","getFlowerAddress"},
         {"吸光标","A_LightChip"},
         {"秒坐坛","miaozuotan"},
         {"返回主页","Main"}
         }
  zbzcd={--装扮子菜单
         --{"全衣柜("..qygkg..")","qyg"},
         {"xa全衣柜备用("..unclosetkg..")","xaqyg"},
         --{"全动作("..unemotekg..")","xaemo"},
         {"临时动作","lsdz"},
         {"衣柜菜单","ssyg"},
         {"绊爱芜湖","banaiwuhu"},
         {"一键芜湖","bawhxh"},
         {"芜湖说明","whsm"},
         {"返回主页","Main"}
         }
  rwzcd={--任务子菜单
         {"️原地任务(稳定)️","ydrw"},
	      {"每日任务","M_MRRW"},
      	  {"️每日季节任务️","jjrw"},
         {"️原地季节任务️","ydzx"},
      	  {"️原地任务修复️","ydrwxf"},
      	  {"返回主页","Main"}
      	  }
   ylzcd={--娱乐子菜单
         {"小黑模式("..xhkg..")","xhms"},
        -- {"巨大蜡烛("..jdlzkg..")","jdlz"},
         --{"植物生长("..zwszkg..")","zwsz"},
         --{"人物隐身("..rwyskg..")","rwys"},
         {"修改天气","xgtq"},
         {"持续大叫","cxdj"},
         {"解锁好友树","jsdz"},
         {"琉璃靓仔","lllz"},
         {"曝光效果","bgxg"},
         {"皇家画质","hjhz"},
         {"云朵美化","ydmh"},
         {"炸房(除自己)","zhafang"},
         {"土豪模式","thms"},
         {"活动召回","hdzh"},
         {"按钮","anniu"},
         {"返回主页","Main"}
         }
         
   rwhjcd={-- 人物环境菜单     
          {"原地不动("..sdkg..")","rwsd"},
         --{"快速奔跑("..pspeedkg..")","xabp"},
        -- {"超级跳("..pjumpkg..")","xaty"},
        -- {"超级游泳("..pdivekg..")","xayy"},
         {"幻影忍者("..pdelaykg..")","xahyrz"},
        -- {"飞机模式("..plainkg..")","xafj"},
        -- {"滑板鞋("..scooterkg..")","xahbx"},
        -- {"超级飞("..spflykg..")","xacjf"},
         {"无限能量1("..wchargekg..")","xawxnl"},
         {"太空飞人("..tkfrkg..")","tkfr"}, 
         {"睡眠粒子("..smlzkg..")","smlz"},
         {"iOS耳机[他人可见]("..bejkg..")","bej"}, 
         --{"香港脚("..xgjkg..")","xgj"},
         --{"飞毛腿("..fmtkg..")","fmt"},
         {"倒立+遁地("..rwdlkg..")","rwdl"},
         --{"无限滑行("..wxhxkg..")","wxhx"},
       --  {"一键遁地[不可关闭]","yjdd"},
       --  {"控制重力","kzzl"},
         {"人物旋转("..rwxzkg..")","rwxz"},
        -- {"踏尸跳","tst"},
         {"返回主页","Main"}
         }
   jkzcd={-- 环境菜单

      --   {"移除风墙("..fqkg..")","xafq"},
         --{"无限烟花("..xayanhuakg..")","xayh"},

         --{"移除云朵("..rcloudskg..")","xaqy"},
        -- {"移除家里海水("..rwaterkg..")","xaqs"},
      --   {"移除传送送门("..rportalskg..")","xaqcsm"},
      --   {"真实画面("..realisimkg..")","zshm"},

         {"快速回家","Fasthome"},

      --   {"无视海水("..wshskg..")","wshs"},

         {"返回主页","Main"}
         }
  gyzcd={--光翼子菜单
         {"可爱无翼("..wykg..")","wuyi"},
         {"修改光翼","xggy"},
         {"原地光翼","ydgy"},
         {"原地光翼备用","ydgy2"},
         {"原地 先祖翼","ydxzy"},
         {"原地 地图翼","yddty"},  
         {"原地翼 测试","ydcsy"},
         {"瞬移光翼","sygy"},
         {"进图吸翼","xiguangyi"},
         {"炸翼","zhayicd"},
         {"返回主页","Main"}
         }
   xjzcd={--献祭子菜单
         {"独狼献祭","xianji"},
         {"拿剩余蜡","nsyl"},
         {"自定义拿蜡次数","A_Nalazu"},
         {"自定义献祭次数","A_ydxj"},
         {"献祭常用","xjcy"},
         {"返回主页","Main"}
         }
slcyzcd={--试炼常用子菜单
         {"水试炼终点","slcyid1"},
         {"土试炼终点","slcyid2"},
         {"风试炼终点","slcyid3"},
         {"火试炼终点","slcyid4"},
         {"返回主页","Main"}
         }
  jdzcd={--景点子菜单
         {"云端景点","Z_enjoyCoor"},
         {"景点彩蛋","jdcd"},
         {"上传景点","scjd"},
         {"复制坐标","fzzb"},
         {"瞬移坐标","syzb"},
         {"返回主页","Main"}
         }
  xhzcd={--新号子菜单
         {"新号开七门","xhkqm"},
         {"一键复刻","ydfks"},
         {"开先祖","kaixianzuMain"},
         {"️一键季节任务️", "ydzx" },
         {"️一键先祖️", "ydxz" },
         {"返回主页","Main"}
         }
  qzzcd={--强制子菜单
         {"好友树("..unnodeskg..")","xahys"},
         {"全体互动","qthddz"},
         {"清除玩家效果","qcsywjxg"},
      --   {"聊天窥屏("..kpkg..")","ltkp"},
         {"返回主页","Main"}
         }
  Mainzcd={--主菜单
         {"每日一键","mryj"},
                  {"一键女巫","yjnv"},
         {"任意门菜单","M_rycs"},
         {"献祭菜单","xj"},
         {"光翼菜单","gy"},
         {"跑图菜单","pt"},
         {"任务菜单","rw"},
         {"魔法菜单","mfxg"},
         {"游戏变速","yxbs"},
         {"好友系统","hyxt"},
         {"人物菜单","rwhj"},
         {"刷新房间","fjsx"},
         {"常用菜单","cy"},
         {"装扮动作菜单","zb"},
         {"原地衣柜","ydyg"},
         {"娱乐菜单","yl"},
         {"环境菜单","jk"},
         {"试炼菜单","sl"},
         {"景点菜单","jd"},
         {"新号菜单","xh"},
         {"交友菜单","qz"},
         {"自动弹琴[仅root用户]","zdtq"},
         {"用户反馈","yhfk"},
         {"脚本聊天室","jklts"},
         {"退出辅助","Exit"},
         {"杀死进程","killgame"}
         }
end
-------菜单函数


function killgame()--结束进程
 gg.processKill()
end
function mryj()--任务
jiasu(10)  ydrw()  ydpt() ydzx()
 jiasu(3)
end

function yjnv()--女巫拿
jiasu(10) xaqyg() qt(57) gg.sleep(800) Teleport({96.2416000366211;38.20657592773438;-1.718523025512695})

 jiasu(3) gg.sleep(5000) 
 gg.sleep(500) 
 gg.sleep(500) 
Teleport({95.57649993896484;38.101503372192383;2.112098217010498}) 
end

function pt()--跑图菜单
jkmmchoice(ptzcd)
end
function rwhj()--人物环境
jkmmchoice(rwhjcd)
end
function cy()--常用菜单
jkmmchoice(cyzcd)
end

function rw()--任务菜单
jkmmchoice(rwzcd)
end

function zb()--装扮菜单
jkmmchoice(zbzcd)
end

function yl()--娱乐菜单
jkmmchoice(ylzcd)
end

function jk()-- 菜单
jkmmchoice(jkzcd," 只要不被举报,稳定奔放。")
end

function gy()--光翼菜单
jkmmchoice(gyzcd)
end

function xj()--献祭菜单
jkmmchoice(xjzcd)
end

function sl()--试炼菜单
jkmmchoice(slcyzcd)
end

function jd()--景点菜单
jkmmchoice(jdzcd)
end

function xh()--新号菜单

jkmmchoice(xhzcd) 

end

function qz()--强制菜单

 jkmmchoice(qzzcd) 

end

-- 主菜单
function Main();A_fjrs()

  FX= "Main"
  jkmmchoice(Mainzcd," 当前地图:"..map[X][3].."    快速回家"..home.."    房间人数:"..rs[1].."人")
end


--循环模块
YUS()
init2()
ydsz()
xaqyg()
gg.addListItems({{address=rwdz,flags=16,name='人物'}})
gjfpy()
gg.setVisible(true)
FX="Main"
while true do
  if gg.isVisible(true) then
    gg.setVisible(false)
    cdsx()
    doAction(FX)

  end
end


