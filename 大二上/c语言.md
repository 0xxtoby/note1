**RSA**

1 RSA 2 RSA 3

3.1 3.2 3.3 3.4 3.5

4
 4.1 p,q,e⇒d
 4.2 e,d,n p,q
 4.3 n p,q, 1
 4.4
 4.5 n
 4.6
 4.7
 4.8 wiener attack
 4.9
 4.10 Rabin
 4.11 d,p d,q ,e,n
 4.12 coppersmith
 4.13 short pad attack + related message attack

4.14

1 RSA

    

2 RSA

3 3.1

n=1

p,e,c

RSA
 2020 5 4RSA RSA

RSA ECC

RSA

ECC

p,q

n=p*q
 e 0<e<φ(n) d*e=1 mod φ(n)

(n,e)

φ(n)=(p-1)*(q-1) φ(n)%e≠0

φ(n) e d (n,d)

nnn

φ(n)

*c*=*m**e* *modn m*=*c**d* *modn*

RSA 1

。示表 以，数函拉欧做叫就法方的值个这算计 ?系关质互成构与个少多有，中之数整正的于等于小在问请，数整正定给意任

)逆互 与 ，下

为则钥私， 为对钥公，此因 模在即( 钥私算计 时同， ， 钥公择选 ，)解分法无( 出算计 数素大个两取选

。多变渐逐在目题型类线曲圆椭，看来势趋前目从。杂复加更理原密加的 ，理原的 于较相。)密 有还法算密加称对非的典经，外以 了除。) 是道 中其，学码密道 共一杯云祥年 :子例型典(

加线曲圆椭(
 影身的 到看能都赛比场一每本基此因，爱喜的人题出受较比，多常非法方击攻可其，

```
是就的要重最最，中法算密加称对非在
```

数函拉欧 理原式公些一的中论数

式方密加 密解与密加

文明出解可即 用套接直么那 为解分可 求 知已 知已

理原密加

击攻
 ) ( 知已

```
   击攻播广数指密加低
       击攻数指小
     解分数约公用利
数参钥公取获件文钥公解分
```

击攻 击攻模共

知已

题例 得里几欧展扩

```
理定逊尔威
号符德让勒
 理定拉欧
    数函拉欧
理原式公些一的中论数
```

密解与密加 理原密加

式方密解

3.2

*letn*=*p**k*11 ∗*p**k*22 ∗...∗*p**k**r**r
\* *φ* ( *n* ) = *φ* ( *p* *k*1 1 ) ∗ *φ* ( *p* *k*2 2 ) ∗ . . . ∗ *φ* ( *p* *k**r* *r* )

*φ*(*n*)=*p**k*11 ∗(1− 1 )∗*p**k*22 ∗(1− 1 )∗...∗*p**k**r**r* ∗(1− 1 ) *p*1 *p*2 *p**r*

*φ*(*n*)=*p**k*11 ∗*p**k*22 ∗...∗*p**k**r**r* ∗(1− 1 )∗(1− 1 )∗...∗(1− 1 ) *p*1 *p*2 *p**r*

*φ*(*n*)=*n*∗(1− 1 )∗(1− 1 )∗...∗(1− 1 ) *p*1 *p*2 *p**r*

*a**φ*(*n*) = 1 *mod n*, *gcd*(*a*,*n*) = 1 *c**d* =(*m**e*)*d*

=*m**e*∗*d* *mod n* =*m*1+*k*∗*φ*(*n*) *mod n*

=*m* ∗ *m**k*∗*φ*(*n*) *mod n
\* =*m* ∗ (*m**φ*(*n*))*k* *mod n* 1

*φ*(1) = 1
 n
 *φ*(*n*) = *n* − 1
 *n* = *p* ∗ *q* (p,q )
 *φ*(*n*) = *φ*(*p*) ∗ *φ*(*q*) = (*p* − 1) ∗ (*q* − 1) *n* = *p**k*

n *p*,2*p*,3*p*,...*p**k*−1 ∗*p*, *p**k*−1 *φ*(*n*)=*p**k* −*p**k*−1 =*p**k* ∗(1− 1*p*)=*n*∗(1− 1*p*)

RSA

1⇒2

*gcd*(*m*, *n*) = 1 *g c d* ( *m* , *n* ) = 1

m=sp

=*m mod n*

∵*n* = *p* ∗ *q*, *gcd*(*m*, *n*) = 1 

∴*m*=*sp m*=*rq*

2

RSA

2

()

的质互是就的下剩么那，个 共下一数

有的质互不 与，虑考上义定从

或

果如 明证可即理定拉欧由接直， 果如

。明证外额要需 ，中其

数素个两的等相不为

:

明证可，此因

理定拉欧

数素为

设妨不

:广推

| 3.3 									3.4 									3.5 									ax+by=gcd(a,b) x,y 									4  4.1 p,q,e⇒d 								 							 								*a**φ*(*n*)/2 = ±1  *p* 1∗2∗3∗...∗(*p*−1)=−1 								 							 								mod *p* 								 						 						 							 								∵*m**φ*(*q*) = 1 *mod q* ∴*m**q*−1 =1*modq* 									∴*m**k*∗(*p*−1)∗(*q*−1) = 1 *mod q* ∴*m**k*∗*φ*(*n*) = 1 *mod q* 									∴*m**k*∗*φ*(*n*) = *tq* + 1 									∴*m**k*∗*φ*(*n*) ∗*m*=(*tq*+1)∗*m * ∵*m* = *sp * ∴*m**k*∗*φ*(*n*)+1 =*tqm*+*m*=*tq*∗*sp*+*m*=*tsn*+*m* ∴*m**k*∗*φ*(*n*)+1 *mod n* = *m mod n * ∴*m**k*∗*φ*(*n*) *mod n* = 1 *mod n* |
| ------------------------------------------------------------ |
| RSA p=473398607161 q=4511491 e=17 d                          |
| ∵ *d* ∗ *e* = 1 *mod φ*(*n*)  ∴ *d* ∗ *e* + *k* ∗ *φ*(*n*) = 1 *mod φ*(*n*) |
| def gcd(a,b): if b == 0: 									return a return gcd(b,a%b) 									# a*x + b*y = gcd(a,b) x,y 									def ext_gcd(a, b): if b == 0: 									return 1, 0 else: 									k = a // b  remainder = a % b  x1, y1 = ext_gcd(b, remainder) x, y = y1, x1 - k * y1 									return x, y 									def inv(e, MOD):  x, y = ext_gcd(e,MOD) return x |
|                                                              |

RSA 3

， ，

出解求 设假，中成生对钥密 次一在

有么那，数素为 设假

回返

法除相转辗 ) (解数整的 求

得里几欧展扩 :解

得里几欧展扩

理定逊尔威

号符德让勒

题例 知已

题例

| RSA                                                          |      | 4    |
| ------------------------------------------------------------ | ---- | ---- |
| (p,q,e)=(473398607161,4511491,17) n=p*q  phi_n = (p - 1) * (q - 1)  d = inv(e, phi_n) assert(gcd(e,phi_n) == 1) print(d) |      |      |
| p,q,e,c 							 						 							p,q,e d 								m |      |      |
| # encrypt 								from Crypto.Util.number import bytes_to_long, long_to_bytes, inverse from Crypto.Util.number import getPrime  from gmpy2 import invert 								flag = b"test.......test" 								e = 65537  # getPrime(512) 512bit p = getPrime(512)  q = getPrime(512)  n = p*q  # bytes_to_long bytes->num  m = bytes_to_long(flag)  c = pow(m, e, n)  print(c) |      |      |
| *p*,*q*,*e* ⇒ *d m*=*c**d* *modn*                            |      |      |
| from Crypto.Util.number import bytes_to_long, long_to_bytes, inverse from Crypto.Util.number import getPrime  from gmpy2 import invert 								p = 11676051195515049069996596285348749900918078079741419763055417273203101611022118459167938039506145514281756244210361136569542410 q = 10315984123984774457662212691496628969472212373691807981769204403439398786435378656107178613432673000807327132053727674042100214 e = 65537  c = 20343085339425793640864363014691172523335794854995674420425397084628460201685540859699058586640215807169674729533033759504677263 								# decrypt 								n = p*q  phi_n = (p-1)*(q-1)  d = inverse(e, phi_n) # or d = invert(e, phin) m = pow(c, d, n)  print(long_to_bytes(m)) |      |      |
| 4.2 e,d,n p,q 								*d* ∗ *e* = 1 *mod φ*(*n*)  *d* ∗ *e* − 1 = *k* ∗ *φ*(*n*)  *φ*(*n*) = (*p* − 1) ∗ (*q* − 1) = *p* ∗ *q* − *p* − *q* + 1 = *n* − *p* − *q* + 1 *p* + *q* = *n* − *φ*(*n*) + 1 |      |      |
| # coding:utf-8 								'''  e,d,n, p,q 								''' 								from Crypto.Util.number import getPrime from gmpy2 import invert, iroot |      |      |
|                                                              |      |      |

子例的体具个一看来们我来下接 ，题问间时是过不文明出求，上手在拿们我被经已 钥私，了开解经已就本基题道这，时 到取获够能当，到觉察以可们我，此因

文明解求后然，

成生码代的面下用利

数素的 个一生产

解求 知已

求 知已

本脚密解

路思题解

RSA 5

e = 65537
 p = getPrime(512)
 q = getPrime(512)
 n = p*q
 phin = (p-1)*(q-1) d = invert(e, phin)

print p print q

\# ----- calculate p,q -----

for k in range(e, 2, -1): if (e*d - 1) % k == 0:

\# x = p+q

x = (k*n + 1 + k - e*d)//k
 \# y = p*q
 y=n
 \# z = (p+q)^2 - 4*p*q = (p-q)^2 z = x**2 - 4*y

\# iroot(a,b): a b (c, True/False), c True c**b = a, False

if iroot(z, 2)[1]:
 z = iroot(z, 2)[0] guess_p = (x+z)//2 guess_q = (x-z)//2 print guess_p print guess_q

4.3n p,q, 1

n http://www.factordb.com/ .pem .pub

yafu

flag.enc N flag EG openssl N e

4.4

e

root@kali:~/ /RSA# openssl rsa -pubin -text -modulus -in public.pem RSA Public-Key: (256 bit)
 Modulus:

00:dc:84:79:8f:78:6d:6d:ab:33:14:46:3e:2c:5f: 27:cd:0d:c4:8a:0f:97:13:da:fc:f9:18:02:eb:bc: b7:1d:5f

Exponent: 65537 (0x10001) Modulus=DC84798F786D6DAB3314463E2C5F27CD0DC48A0F9713DAFCF91802EBBCB71D5F writing RSA key
 -----BEGIN PUBLIC KEY----- MDwwDQYJKoZIhvcNAQEBBQADKwAwKAIhANyEeY94bW2rMxRGPixfJ80NxIoPlxPa /PkYAuu8tx1fAgMBAAE=
 -----END PUBLIC KEY-----

https://blog.csdn.net/like98k/article/details/79352076

4.5 n

n

2 n p gcd(n1,n2 p

\# coding:utf-8

'''
 n

'''

import gmpy2
 from Crypto.Util.number import GCD

n1 = 9051013965404084482870087864821455535159008696042953021965631089095795348830954383127323853272528967729311045179605407693592 665683311660581204886571146327720288455874927281128121117323579691204792399913106627543274457036172455814805715668293705603675386 878220947722186914112990452722174363713630297685159669328951520891938403452797650685849523658191947411429068829734053745180460758 604283051344339641429819373112365211739216160420494167071996438506850526168389386850499796102003625404245645796271690310748804327 n2 = 1322594839617960381606204641871721479266851241362509156999752436424399599196101889415005920782409383742045137524055031005020 939896450631851899162014257592662378041153225723070198582162942572203060872203557069047417125923815394709531030352283197166466606

。 和 的中件文钥公取提 ， (出取提，钥公析分要需你，)的类之

用先般一 。 到得文密密解去后然，钥私复恢段手击攻种各过通，) 做叫常通(文密和)件文的尾结 或 以是常通(件文钥公个一给会人题出

出求 用使试尝以可们我时这， 数因的同相了用使 个 有会能可中其， 个多出给会般一目题 解分数约公用利

)讲多再不就，过及提经已个这(具工 者或站网 用使以可， 解分于关 文明出解可即 用套接直么那 为解分可

为则否 即，进开能果结表代则 为面后，分部整取为 中其 是果结的到得，整取，方次 开 对

```
数参钥公取获件文钥公解分
```

解分数约公用利

考参可，令命他其有还

面桌

:如例

RSA 6

754264903446162172565623486900550129342397518470192972917007728025143621616729305856003008900614022437542567957118178720698271247 726143257953798127805575534457376707695179331206248027500456465759026371981603356413949710994207370175501187315320536623858566574 3

p = gmpy2.gcd(n1, n2) # or p = GCD(n1, n2) print 'gcd(n1, n2):\n', p
 q1 = n1 // p
 q2 = n2 // p

print 'q1 is:\n', q1 print 'q2 is:\n', q2

4.6

e e=3 m^e < n c
 m^e n m^e = c+k*n k

\# coding:utf-8

'''

'''

from Crypto.Util.number import getPrime, bytes_to_long, long_to_bytes, inverse from gmpy2 import invert, iroot

flag = "test.......test"

e=3
 p = getPrime(512)
 q = getPrime(512)
 n = p*q
 m = bytes_to_long(flag)
 c = pow(m, e, n)
 print c
 \#c3
 m = iroot(c, e)[0]
 assert iroot(c,e)[1] == True print long_to_bytes(m)

\# -------- --------

flag = "test.........test.........test.........test" m = bytes_to_long(flag)
 c = pow(m, e, n)

k=0 while 1:

if iroot(k*n+c, e)[1]:
 m = iroot(k*n+c, e)[0]
 print "when k={}, we get the flag:".format(k) print long_to_bytes(m)
 break

k+=1

4.7

**2020cybrics-broken_ invitation**

n 5. m e e=3 (n,c)

CRT

这， 组三了出给目题，时

。解求理定余剩国中用以可们我候时 如例，小较且而，同相 的用使时密加行进 对，时同，击攻模共 用法无是但， 个多出给出目题

```
子式下以如，的组程方余同性线元一决解来用)  (理定余剩国中
               :理定余剩国中下一绍介单简先首
```

。破爆以可此因，大不 ，中
 。可即方开行进 对接直此因， 得使， 如，小较

:题例 击攻播广数指密加低

在即，大很是不并是但，大 比 :展扩 击攻数指小

展扩

根方次 开 对接直

击攻数指小

RSA 7

m1,m2,...mn

RSA e=3 m^3 = c1 mod n1
 m^3 = c2 mod n2
 m^3 = c3 mod n3

CRT

CRT x n,c

m^3 3

\# coding:utf-8

'''

'''

from Crypto.Util.number import getPrime, bytes_to_long, long_to_bytes from gmpy2 import iroot
 try:

from libnum import solve_crt except:

print "no module named libnum: please use `pip install libnum` to obtain it." exit(0)

flag = "test.........test.........test.........test.....longlong"

m = bytes_to_long(flag) e=3
 ns = []
 cs = []

for i in range(e):
 p = getPrime(512)
 q = getPrime(512)
 n = p*q
 c = pow(m, e, n)
 ns.append(n)
 cs.append(c)
 print "c{} = {}".format(i+1, hex(c)) print "n{} = {}".format(i+1, hex(n))

\# -------- -------- # csns
 m = solve_crt(cs, ns)
 assert iroot(m, 3)[1] == True

m = iroot(m, 3)[0] print "solve:"
 print long_to_bytes(m)

4.8 wiener attack

**2020ciscn-bd 2020 -simpleRsa**

e,n,c e n wienerAttack n

\# coding: utf-8

'''
 wiener attack n

'''

import gmpy2
 from Crypto.Util.number import bytes_to_long, long_to_bytes

\#

def continuedFra(x, y): cF = []

while y:
 cF += [x / y]

x, y = y, x % y return cF

def Simplify(ctnf): numerator = 0

denominator = 1
 for x in ctnf[::-1]:

numerator, denominator = denominator, x * denominator + numerator

解分来数函

用套接直， 近接，大别特 中其， 了出给目题:征特

)阶进( 杯云祥 ;

:题例

和 知已 解求行进理定余剩国中用利

根方次 开其对后然， 出解求 用利以可就们我此因

子式下以个三有就们我，么那) (组三了出给目题时同， 设假，来中 到回

。算计行进来数函库 的⻔专用调以可们我为因，理原道知要需许不们我， 解求何如于至。景场用应的 是就这。数整的质互两两是 ，中其

数分连为开展

解分 用使

击攻播广

| RSA                                                          |      | 8    |
| ------------------------------------------------------------ | ---- | ---- |
| return (numerator, denominator) # 							 					 					 						 							def 								# 								def 								def 							 						 							calculateFrac(x, y):  cF = continuedFra(x, y)  cF = map(Simplify, (cF[0:i] for i in xrange(1, len(cF)))) return cF 							 					 					 						 							solve_pq(a, b, c):  par = gmpy2.isqrt(b * b - 4 * a * c)  return (-b + par) / (2 * a), (-b - par) / (2 * a) 								wienerAttack(e, n):  for (d, k) in calculateFrac(e, n): 								if k == 0: continue  if (e * d - 1) % k != 0: continue phi = (e * d - 1) / k  p, q = solve_pq(1, n - phi + 1, n) if p * q == n: 								return abs(int(p)), abs(int(q)) print 'not find!' 								exit(0) 							 					 					 						 							n = 086023159482786712759291169541633901936290854044069486201989034158882661270017305064348254800318759062921744741432214818915527537 124001063995865927527037625277330117588414586505635959411443039463168463608235165929831344586283875119363703480280602514451713723 663297066810128769907278246434745483846869482536367912810637275405943566734099622063142293421936734750356828712268385319217225803 602442033960930413469179550331907541244416573641309943913383658451409219852933526106735587605884499707827  e = 11850552481503020257392808424743510851763548184936536180317707155841959788151862976445957810691568475609821000653594584717037 528429828330763571556164988619635320288125983463358648887090031957900011546300841211712664477474767941406651977784177969001025954 167441377912326806132232375497798238928464025466905201977180541053129691501120197010080001677260814313906843670652972019631997467 352264392296894192998971542816081534808106792758008676039929763345402657578681818891775091140555977382868531202964486261123748663 752490909455324860302967636149379567988941803701512680099398021640317868259975961261408500449965277690517  c = 94721931745755366169540916867519648738366972375001988844515304693003244706715553107913351851336796972070073746202259007755021 626908481356154316245573893046574108809814547777375874204260918796540026442810664747150745366116112526778823963844536411274875158 451760695747546066705180314722351447953765268544844421352998188685255399235687052030422655372041111531511191052876489129087717104 196484458268830690302856517637260034134187643019882280774155996656166375010561162904768612802405771455158754306653942160542227886 97052979429015400411487342877096677666406389711074591330476335174211990429870900468249946600544116793793 								# ------wiener attack----- 								p, q = wienerAttack(e, n) 								print '[+]Found!'  print ' [-]p =',p  print ' [-]q =',q  d = gmpy2.invert(e, (p-1)*(q-1)) print ' [-]d =', d 								print ' [-]m is:', long_to_bytes(pow(c, d, n)) 							 					 					 						 							12238605063252292170613110607692779326628090745751955692266649177882959231822580682548279800443278979485092243645806337103841 |      |      |
| 4.9 								m^e1 = c1 mod n m^e2 = c2 mod n 							 					 					 						 							**20205space-rosb** 							 					 					 						 							emn 								m^(a*e1+b*e2 a*e1+b*e21 m^(a*e1+b*e2)=c1^a * c2^b m egcd a,b |      |      |
| # coding:utf-8 								''' ''' 								from Crypto.Util.number import getPrime, bytes_to_long, long_to_bytes, inverse 								def egcd(b, n):  (x0, x1, y0, y1) = (1, 0, 0, 1) while n != 0: 								(q, b, n) = (b // n, n, b % n) (x0, x1) = (x1, x0 - q * x1) |      |      |
|                                                              |      |      |

我里这。了 出解能就们我样这，

出算计来) (得里几欧展扩用使要需们 时同。 得使 出造构是法想的们我此因

子式个两到得以可们我，件条的出给目题据根 同相是但，密加行进个一同对的同不的用使目题:征特 :目题

击攻模共

击攻模共

理定达⻙解

简化数分连

RSA 9

(y0, y1) = (y1, y0 - q * y1) return (b, x0, y0)

flag = "test.........test.........test.........test.....longlong"

m = bytes_to_long(flag) e1 = 31
 e2 = 65537

m ---

p =
 q =
 n =
 c1 = pow(m, e1, n) c2 = pow(m, e2, n)

\# ---

getPrime(512) getPrime(512) p*q

_, a,
 print
 \# a =
 m = pow(c1, a, n) * inverse(pow(c2, -b, n), n) % n

print "so, m = c1**{} * c2**{} mod n".format(a, b) print "m =", long_to_bytes(m)

b = egcd(e1, e2) a, b
 21141, b = -10

4.10 Rabin

e=2

\# coding:utf-8

''' e=2

'''

import gmpy2
 import string
 from Crypto.Util.number import bytes_to_long, long_to_bytes, inverse

flag = 'test.........test.........test'

m = bytes_to_long(flag)
 p = 275127860351348928173285174381581152299 q = 319576316814478949870590164193048041239 e=2
 n = p*q
 c = pow(m, e, n)

yp = gmpy2.invert(p,q)
 yq = gmpy2.invert(q, p)
 \# mpmq
 mp = pow(c, (p + 1) / 4, p) mq = pow(c, (q + 1) / 4, q)

\#

a = b = c = d = # for

a,b,c,d

(yp * p * mq + yq * q * mp) % n n - int(a)
 (yp * p * mq - yq * q * mp) % n n - int(c)

a,b,c,d

m in (a,b,c,d):
 if "test" in long_to_bytes(m):

print long_to_bytes(m)

4.11 d,p d,q ,e,n

**2019hxb-easyRsa**

c≡m^e mod n m≡c^d mod n φ(n)=(p−1)∗(q−1) d∗e≡1 mod φ(n) **dp****≡****d mod (p−1)**

:目题 ) ( 知已

个一的中

是果结的终最

和 算计

:征特 击攻

解求击攻模共用利

算计

合适

| e*dp = 1 mod p-1  e*dp = k(p-1) + 1 = kp - k+1 e*dp+k-1 = kp |
| ------------------------------------------------------------ |
| # coding:utf-8 									'''  dp (dp = d % (p-1)) 									''' 									from Crypto.Util.number import getPrime, bytes_to_long, long_to_bytes from gmpy2 import iroot, invert 									flag = "test.........test.........test.........test.....longlong" 									m = bytes_to_long(flag) e = 65537  p = getPrime(512)  q = getPrime(512) 									n = p*q  d = invert(e, (p-1)*(q-1)) c = pow(m, e, n)  dp = d%(p-1) 									print c print dp 									# --- know dp --- 									def getd(n,e,dp):  for i in range(1,e): 									if (dp*e-1)%i == 0:  if n%(((dp*e-1)/i)+1)==0: 									p=((dp*e-1)/i)+1 q=n/(((dp*e-1)/i)+1) phi = (p-1)*(q-1)  d = invert(e,phi) return d 									guess_d = getd(n, e, dp) m = pow(c, d, n) 									print long_to_bytes(m) |
| 4.12 coppersmith 									**2019 -copperstudy** 									coppersmith 									coppersmith python 									 								 							 								sagemath 								 							 								https://sagecell.sagemath.org/ |
| n=0x2680048649769800c79ec1f3ceab3909b8dc665c2f44dea93678a3c604c1e87cd7500a59e126bbeed10318c83807c7701d8968448200a43b7f64e697129c8 fa88b52f0e62ce3166a0d817f195452e0de6fe27e1d2939a88756e2b38694837513199aa6d92ba88dd895020a53ef007b0f57478c7f363d4d262db4c2da5e8b15 75 c=0xbdf9abbdf60072d7421a33bd7294c76fcea8f5cac435e552b003d9192de4391a049fc8911b15378091bd4f87a6173671abcd13e92d353d5b1f0798d49538d 4da98931b5f021ca7743036b996893b8d81910859edba619c28ec237e5f7abc0d9a4fdb1a85ba44c22b9031d3317998eb41d4d11ab34ab1f731ba50697317029c d mbar=0x472796951dbf2909faba23a804ff52df69a44e166d7a7bd2c57eeba22e4ea2dcb99123fdb17db038a13af1061c41daab206a88881c8023000000000000 000000 									kbits = 72  e=3  PR.<x> = PolynomialRing(Zmod(n))  f = (mbar + x)^e - c  x0 = f.small_roots(X=2^kbits, beta=1)[0] # find root < 2^kbits with factor = n print mbar + x0  print x0 |
|                                                              |

RSA 10

缺， 用使以可站网的线在有过不，烦麻较比，境环的 装安要需击攻 可即景场用应个几的⻅常会要只家大，活灵常非用应，识知论数及涉击攻

用利且而

板模用套 位高文明知已

库 的它其用能不是点

杯网强 :目题 击攻

知已

即

即 以所

RSA 11

\2. pq

n=0x63d1b2ecd4fd3da6ce2afe6c7b2e9086920a461f1b6a0d0c5782563c1e6af681cd03ea7ff4b4cb5d6f980fca6f605db0376c337e0921798f395fb0088b895 eebe4b977251c9000c9c80055edbdc89068e0e88f311641407c8082aaab9497ee685005063af64b735143d18bbb0c72ee02220bd68c8250e5bcfde8d3d7e66bf2 b5 p=0x8b8a9cc1a5373864eaf7671d0a12547163c83408f1e99dbfd531f86dc7af585bae265a749f63d05016b4596ecdc5308500000000000000000000000000000 000

p_fake = p+0x100000000000000000000000000000000 pbits = 512 #p
 kbits = 128 #
 pbar = p_fake & (2^pbits-2^kbits)

print "upper %d bits (of %d bits) is given" % (pbits-kbits, pbits)
 PR.<x> = PolynomialRing(Zmod(n))
 f = x + pbar
 x0 = f.small_roots(X=2^kbits, beta=0.4)[0] # find root < 2^kbits with factor >= n^0.4 print x0 + pbar

\3. d

def partial_p(p0, kbits, n):
 PR.<x> = PolynomialRing(Zmod(n)) nbits = n.nbits()

f = 2^kbits*x + p0
 f = f.monic()
 roots = f.small_roots(X=2^(nbits//2-kbits), beta=0.3) # find root < 2^(nbits//2-kbits) with factor >= n^0.3 if roots:

x0 = roots[0]
 p = gcd(2^kbits*x0 + p0, n) return ZZ(p)

def find_p(d0, kbits, e, n):

X = for

var('X')

k in xrange(1, e+1):
 results = solve_mod([e*d0*X - k*X*(n-X+1) + k*n == X], 2^kbits)

for

x in results:
 p0 = ZZ(x[0])
 p = partial_p(p0, kbits, n) if p:

return p

if __name__ n=0x5c6b8458509910007051be15d867161643d8c62a3032200261b8fef53403d4a7639e4f810fc34ddbce0c49156bab8686ecea8a2cfeba2349304535e48

3fd40cfedb8c45163f130f98d23edb8bca3c049f34f11c92c9ec7df9a9096221564a59f9e165106144b4b2f890d19e1bc82d24b4e2fe27b34428fd635f49f3e58 9fb5a7

e=3

d = 0xc54fb4b61153358ca26946efd6c472b248715edb73d853900400e2488535847b5030dd97a619693fc9bf8151a1562b291193f87518fae5c1674266c d6f0a91bb

nbits = n.nbits()
 kbits = floor(nbits*(0.5))
 d0 = d & (2^kbits-1)
 print "lower %d bits (of %d bits) is given" % (kbits, nbits)

p = find_p(d0, kbits, e, n) print p

== '__main__':

\4. Boneh Durfee
 n,e,c e *d* < *n*0.292 wiener attack *d* < 1/3 ∗ *n*0.25

\#!/usr/bin/env sage

\# This code is taken from https://github.com/mimoo/RSA-and-LLL-attacks
 \# TODO: make this a submodule w/patch file so we do not have to distribute it as a .sage file

import time

```
目题到遇议建，似相常非景场用应的)
```

( 的面前和里这意注，

:板模用套接直。下一试尝都者两时 时同，大别特 ， 知已

击攻

数位知未 数位的

位低的 知已

板模用套 位高的个一中其 ， 知已

| RSA                                                          |      | 12   |
| ------------------------------------------------------------ | ---- | ---- |
| ############################################ # Config ########################################## 								"""  Setting debug to true will display more informations about the lattice, the bounds, the vectors...  """  debug = False 								"""  Setting strict to true will stop the algorithm (and return (-1, -1)) if we don't have a correct upperbound on the determinant. Note that this doesn't necesseraly mean that no solutions  will be found since the theoretical upperbound is usualy far away from actual results. That is why you should probably use `strict = False`  """  strict = False 							 					 					 						 							"""  This is experimental, but has provided remarkable  so far. It tries to reduce the lattice as much as  while keeping its efficiency. I see no reason not  this option, but if things don't work, you should  disabling it  """  helpful_only = True  dimension_min = 7 # stop removing if lattice reaches that dimension 								############################################ # Functions ########################################## 								# display stats on helpful vectors 								def helpful_vectors(BB, modulus): nothelpful = 0 								for ii in range(BB.dimensions()[0]): if BB[ii,ii] >= modulus: 								nothelpful += 1  # print nothelpful, "/", BB.dimensions()[0], " vectors are not helpful" 								# display matrix picture with 0 and X 								def matrix_overview(BB, bound): 							 					 					 						 							for 							 						 							ii in range(BB.dimensions()[0]):  a = ('%02d ' % ii)  for jj in range(BB.dimensions()[1]): 								a += '0' if BB[ii,jj] == 0 else 'X' if BB.dimensions()[0] < 60: 								a += ' '  if BB[ii, ii] >= bound: 								a += '~' # print a 							 					 					 						 							# tries  # we start at current = n-1 (last vector)  def remove_unhelpful(BB, monomials, bound, current): 								# end of our recursive function 								if current == -1 or BB.dimensions()[0] <= dimension_min: return BB 								# we start by checking from the end 								for ii in range(current, -1, -1): # if it is unhelpful:  if BB[ii, ii] >= bound: 								affected_vectors = 0  affected_vector_index = 0  # let's check if it affects other vectors for jj in range(ii + 1, BB.dimensions()[0]): 								# if another vector is affected: # we increase the count  if BB[jj, ii] != 0: 								affected_vectors += 1 affected_vector_index = jj 								# level:0  # if no other vectors end up affected # we remove it  if affected_vectors == 0: 							 					 					 						 							to remove unhelpful vectors 							 					 					 						 							results it can to use try |      |      |
|                                                              |      |      |

| RSA                                                          |      | 13   |
| ------------------------------------------------------------ | ---- | ---- |
| # nothing 								return BB 							 						 							check 								affected_deeper = True  for kk in range(affected_vector_index + 1, BB.dimensions()[0]): 								# if it is affecting even one vector  # we give up on this one  if BB[kk, affected_vector_index] != 0: 								affected_deeper = False  # remove both it if no other vector was affected and  # this helpful vector is not helpful enough  # compared to our unhelpful one  if affected_deeper and abs(bound - BB[affected_vector_index, affected_vector_index]) < abs(bound - BB[ii, ii]): 								# print "* removing unhelpful vectors", ii, "and", affected_vector_index 								BB = BB.delete_columns([affected_vector_index, ii]) BB = BB.delete_rows([affected_vector_index, ii]) monomials.pop(affected_vector_index) monomials.pop(ii) 								BB = remove_unhelpful(BB, monomials, bound, ii-1) 								return BB happened 							 					 					 						 							# print "* removing unhelpful vector", ii 								BB = BB.delete_columns([ii]) BB = BB.delete_rows([ii]) monomials.pop(ii)  BB = remove_unhelpful(BB, return BB 								# level:1  # if just one was affected we  # if it is affecting someone else elif affected_vectors == 1: 							 					 					 						 							"""  Returns:  * 0,0  * -1,-1  * x0,y0  """  def boneh_durfee(pol, modulus, 								"""  Boneh and Durfee revisited  finds a solution if:  * d < N^delta  * \|x\| < e^delta  * \|y\| < e^0.5  whenever delta < 1 - sqrt(2)/2 ~ 0.292 """ 								# substitution (Herrman and May) 								PR.<u, x, y> = PolynomialRing(ZZ)  Q = PR.quotient(x*y + 1 - u) # u = xy + 1 polZ = Q(pol).lift() 								UU = XX*YY + 1 								# x-shifts 								gg = []  for kk in range(mm + 1): 								for ii in range(mm - kk + 1):  xshift = x^ii * modulus^(mm - kk) * polZ(u, x, y)^kk gg.append(xshift) 								gg.sort() 								# x-shifts list of monomials 								monomials = []  for polynomial in gg: 								for monomial in polynomial.monomials(): if monomial not in monomials: 								monomials.append(monomial) monomials.sort() 								# y-shifts (selected by Herrman and May) 								for jj in range(1, tt + 1):  for kk in range(floor(mm/tt) * jj, mm + 1): 								yshift = y^jj * polZ(u, x, y)^kk * modulus^(mm - kk) yshift = Q(yshift).lift()  gg.append(yshift) # substitution 								# y-shifts list of monomials 								for jj in range(1, tt + 1):  for kk in range(floor(mm/tt) * jj, mm + 1): 							 					 					 						 							if it  if `strict=true`, and determinant doesn't bound the solutions of `pol` 							 					 					 						 							fails 							 					 					 						 							monomials.append(u^kk * y^jj) 							 					 					 						 							mm, tt, XX, YY):  by Herrmann and May 							 					 					 						 							monomials, bound, ii-1) |      |      |
|                                                              |      |      |

| RSA                                                          |      | 14   |
| ------------------------------------------------------------ | ---- | ---- |
| # construct lattice B 								nn = len(monomials) BB = Matrix(ZZ, nn) for ii in range(nn): 								BB[ii, 0] = gg[ii](0, 0, 0) for jj in range(1, ii + 1): 								if monomials[jj] in gg[ii].monomials():  BB[ii, jj] = gg[ii].monomial_coefficient(monomials[jj]) * monomials[jj](UU,XX,YY) 								# Prototype to reduce the lattice 								if helpful_only:  # automatically remove  BB = remove_unhelpful(BB, monomials, modulus^mm, nn-1) # reset dimension  nn = BB.dimensions()[0]  if nn == 0: 								# print "failure" 								return 0,0 								# check if vectors are helpful 								if debug:  helpful_vectors(BB, modulus^mm) 								# check if determinant is correctly bounded 								det = BB.det()  bound = modulus^(mm*nn) if det >= bound: 								# print "We do not have det < bound. Solutions might not be found." # print "Try with highers m and t."  if debug: 								diff = (log(det) - log(bound)) / log(2) 								print("size det(L) - size e^(m*n) = ", floor(diff)) if strict: 								return -1, -1 # else: 								# print "det(L) < e^(m*n) (good! If a solution exists < N^delta, it will be found)" 								# display the lattice basis 								if debug:  matrix_overview(BB, modulus^mm) 								# LLL 								BB = BB.LLL() 								# transform vector 1 & 2 -> polynomials 1 & 2 								PR.<w,z> = PolynomialRing(ZZ) pol1 = pol2 = 0  for jj in range(nn): 								pol1 += monomials[jj](w*z+1,w,z) * BB[0, jj] / monomials[jj](UU,XX,YY) pol2 += monomials[jj](w*z+1,w,z) * BB[1, jj] / monomials[jj](UU,XX,YY) 								# resultant 								PR.<q> = PolynomialRing(ZZ) rr = pol1.resultant(pol2) 								if rr.is_zero() or rr.monomials() == [1]:  # print "the two first vectors are not independant" return 0, 0 								rr = rr(q, q) # solutions 								soly = rr.roots() 								if len(soly) == 0:  # print "Your prediction (delta) is too small" return 0, 0 								soly = soly[0][0]  ss = pol1(q, soly)  solx = ss.roots()[0][0] 								# 								return solx, soly 								def main(N,e): ############################################ # How To Use ########################################## |      |      |
|                                                              |      |      |

RSA 15

\# the hypothesis on the private exponent (max 0.292) delta = .26 # d < N^delta

\#

- \#  Lattice (tweak those values) #
- \#  you should tweak this (after a first run)

m = 4 # size of the lattice (bigger the better/slower)

\# might not be a good

t = int((1-2*delta) *

1. X  = 2*floor(N^delta)
2. Y  = floor(N^(1/2))

idea to tweak these
 m) # optimization from Herrmann and May # this _might_ be too much
 \# correct if p, q are ~ same size

\#

- \#  Don't touch anything below #

- \#  Problem put in equation

  P.<x,y> = PolynomialRing(ZZ) A = int((N+1)/2)
   pol = 1 + x * (A + y)

  \#

- \#  Find the solutions! #

- \#  Checking bounds

  if debug:
   print("=== checking values ===")
   print("* delta:", delta)
   print("* delta < 0.292", delta < 0.292) print("* size of e:", int(log(e)/log(2))) print("* size of N:", int(log(N)/log(2))) print("* m:", m, ", t:", t)

  \# boneh_durfee

  if debug:
   print("=== running algorithm ===") start_time = time.time()

  solx, soly = boneh_durfee(pol, e, m, t, X, Y)

  if solx > 0:
   \# print("=== solutions found ===") if debug:

  print("x:", solx) print("y:", soly)

  d = int(pol(solx, soly) / e)

  print(d) else:

  print(0) if debug:

  print("=== %s seconds ===" % (time.time() - start_time)) if __name__ == "__main__":

  import sys

  n = 0xbadd260d14ea665b62e7d2e634f20a6382ac369cd44017305b69cf3a2694667ee651acded7085e0757d169b090f29f3f86fec255746674ffa8a6a3e 1c9e1861003eb39f82cf74d84cc18e345f60865f998b33fc182a1a4ffa71f5ae48a1b5cb4c5f154b0997dc9b001e441815ce59c6c825f064fdca678858758dc2c ebbc4d27

  e = 0x11722b54dd6f3ad9ce81da6f6ecb0acaf2cbc3885841d08b32abc0672d1a7293f9856db8f9407dc05f6f373a2d9246752a7cc7b1b6923f1827adfae efc811e6e5989cce9f00897cfc1fc57987cce4862b5343bc8e91ddf2bd9e23aea9316a69f28f407cfe324d546a7dde13eb0bd052f694aefe8ec0f5298800277db ab4a33bb

  main(n,e)

4.13 short pad attack + related message attack

**2020defenit-double 2020das7-ezrsa**

*c*1=*m**e* mod*n*

```
:如例。系关性线在存间之文明的间之密加组两知已
         ;          :题例
```

RSA 16

*c*2=(2∗*m*+*diff*)*e* mod*n
\* short pad attack diff related message attack m

defenit-double task.sage

\#----2020 Defenit CTF

from Crypto.PublicKey import RSA from hashlib import md5
 import binascii

nBitSize = 2048
 e=3
 Flag = b'XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX'

key = RSA.generate(nBitSize) M1 = Flag + md5(Flag).digest()

M2 = Flag + md5(b'One more time!' + Flag).digest() M1 = int(binascii.hexlify(M1),16)

M2 = int(binascii.hexlify(M2),16) C1 = Integer(pow(M1,e,key.n))

C2 = Integer(pow(M2,e,key.n))

with open('out.txt','w') as f: f.write('n = ' + hex(key.n)+'\n') f.write('C1 = '+ hex(C1)+'\n') f.write('C2 = ' + hex(C2)+'\n')

\# censored

solve.py

n = 0xcfb6152ae5a6f9a40e97f84e0869ac7e20f90bfa0318df1878dc69eba44df38e549cda7946dc6ceebdd8bac4c0b94053d6d7044d30ff3ce6c55faeeb120 d01c77dc2f1633af9ead59f6356bba03c43252ea2fed558252dfea465b108fc3261f080f17fd3db442b3e5e6cfceb6cbcc2323683db5f862bd1df093e73b7373a 77750f4a3cbf38c44559b1252981f0d9325b10d90dbdf44cc982f4c7f955025b639cf9736977d84253b3473001cc0778776ce3d8442d3f300d65efb920ca289d8 321b38f2eaf0314e9c14acea509709852839a7367dba5efd03f41e595b51a69a96ee1ea7626496746a318b8583a2bbc8920c25c085f7237c248530b847f5d146f d3

C1 = 0x86a4cc0a6a8f22fe35b11870b741495a9d9abc84e1ec76e03bd3495832b260aa9014b621bf515258ba33c72f94e75df8ab3969bedc86dd946af79cb0f3 33ae16267d4728ad5b3e48ff72439a159b0b1d0cd5303765607fbe58353361ae7ac27eabc0bebdecc2bcaeb4a18a3463deb4527d7078d9ed9141d79e3e819e2a4 07ce6a71933c587e4da51a2d936c1233247246936880de615db6511b2588977b6e974ff900daa5901af0df1d4623cbdb6b5939082621397bb20b6da3f40d0020d 16fa2d9a5820bf2135725d164d338684809084353efea1c8339d4367e152a54ca36e42e94f0cd67392af2fa4ade80e3ba6173b642c3a9848b65d5214ac870786a a3e

C2 = 0x79f267c0b913f21f508a65d85e43a95e28896f92d127feeabe2e5f8068f518ae2fc9315753cd3eb116a4a8410b65ebfc70ed3c183d034ff48296f919a8 0564e5c91fcf7c9d3ffbc101dc3d155703609d6be3546d6edabbb27201543a93172d9b24a19835c298f6cae8f0ead507971463549fc9b165000fd9ea75b5181a3 61769fed258091be76ffccdf347d404a95d6b7f33ee4bd2d61e7b2c935cc93394b69cf281fed2ebebb5e5174e0a3a820cdb9ed16a0bebb7dc919cba560a99d47d b2d35a3cd92e3ace4cca42666c2cc3b85705796690941b3861a468ec07fb178e057ff6327b0514830d85535d5d7fb9a3d85ab46ae89842cc7e3af06d6f6a1eeef 1ae

e=3

PRxy.<x,y> = PolynomialRing(Zmod(n)) PRx.<xn> = PolynomialRing(Zmod(n)) PRZZ.<xz,yz> = PolynomialRing(Zmod(n))

\# short pad atttack

g1 = x**e - C1
 g2 = (x + y)**e - C2

q1 = g1.change_ring(PRZZ) q2 = g2.change_ring(PRZZ)

h = q2.resultant(q1)
 \# need to switch to univariate polynomial ring
 \# because .small_roots is implemented only for univariate h = h.univariate_polynomial() # x is hopefully eliminated h = h.change_ring(PRx).subs(y=xn)
 h = h.monic()

roots = h.small_roots(X=2**128, beta=0.3) assert roots, "Failed1"

diff = roots[0]

:例为目题的 以 出解求 过通再后然。值 取获 过通先首

| RSA                                                          |      | 17   |
| ------------------------------------------------------------ | ---- | ---- |
| if diff > 2**32: diff = -diff 								C1, C2 = C2, C1  print "Difference:", diff 								# related message attack 								x = PRx.gen()  g1 = x**e - C1  g2 = (x + diff)**e - C2 								# gcd 								while g2:  g1, g2 = g2, g1 % g2 								g = g1.monic()  assert g.degree() == 1, "Failed 2" 								msg = -g[0]  # convert to str  h = hex(int(msg))[2:].rstrip("L") h = "0" * (len(h) % 2) + h  print h.decode("hex") |      |      |
| 4.14 p,e,c 								**2020 -more_calc** 								npnq m<p pm 								task.py |      |      |
| import gmpy2  from Crypto.Util.number import * 								flag = b"flag{xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx}" 								p = getStrongPrime(2048)  for i in range(1, (p+1)//2): 								s += pow(i, p-2, p) s=s%p 								q = gmpy2.next_prime(s)  n = p*q  e = 0x10001  c = pow(bytes_to_long(flag), e, n) print(p) 								print(c) #27405107041753266489145388621858169511872996622765267064868542117269875531364939896671662734188734825462948115530667205007939029 215517180761866791579330410449202307248373229224662232822180397215721163369151115019770596528704719472424551024516928606584975793 350814943997731939996459959720826025110179216477709373849945411483731524831284895024319654509286305913312306154387754998813276562 173335189450448233216133842189148761197948559529960144453513191372254902031168755165124218783504740834442379363311489108732216051 566953498279198537794620521800773917228002402970358087033504897205021881295154046656335865303621793069 #35055918683748883282174784323651813560520737603185800227424500428762264933021511381871995418539707283801414497303232960090541986 190867832897131815320508500774326925395739528242032566313216102210036548100374594081897428098804503420454038574457280610255242042 832626554192534670284369336699175346822030007088865173250252079700270724860427575514471342164997149244044205247072315311115645755 855836214700200464613652201134426101746190195358346246762242881016710707928119020973125199597600335220176686188732073999025860155 060600538887296782517962617671450347555788381054344555539001456268680189452831160062315698482986474322296387716709989292671747978 922668181058489406663507675599642320338049377613048817085979874567772781052867215035033348050642450667612710852648837001109914769 887507004392552421783737965416800917979813137835262317794775319294801257483177741372991005066875900770459644762548438474388076655 842822437141772648037236281057239552272508379892613346840960049192531743799845858272389712078645821963027561694961956409973354276 629777068204456160534409039477757097372521171307620184694243888389707840806777932547158990704118642378158004690358831695861544319 6819133852367565049467076710376395085898875495653237178198379421129086523 |      |      |
| q pmm<p                                                      |      |      |
| from Crypto.Util.number import *  p = 27405107041753266489145388621858169511872996622765267064868542117269875531364939896671662734188734825462948115530667205007939 029215517180761866791579330410449202307248373229224662232822180397215721163369151115019770596528704719472424551024516928606584975 793350814943997731939996459959720826025110179216477709373849945411483731524831284895024319654509286305913312306154387754998813276 562173335189450448233216133842189148761197948559529960144453513191372254902031168755165124218783504740834442379363311489108732216 051566953498279198537794620521800773917228002402970358087033504897205021881295154046656335865303621793069  c = 35055918683748883282174784323651813560520737603185800227424500428762264933021511381871995418539707283801414497303232960090541 986190867832897131815320508500774326925395739528242032566313216102210036548100374594081897428098804503420454038574457280610255242 |      |      |
|                                                              |      |      |

。出解接 直能就们我，话的 的置设人题出果如， 解求试尝来 用试尝们我此因。度难有很上际实这但， 出算们我让是意本的目题，然显

。效有很但，解期预非个一是算这。 出解去 接直用以可么那， 文明的目题果如候时个这。解求你要需，来起密加被则子因的个一另而，共一中其你诉告是而，你诉告会不中目题候时些有

杯云祥 :目题 知已

RSA 18

042832626554192534670284369336699175346822030007088865173250252079700270724860427575514471342164997149244044205247072315311115645 755855836214700200464613652201134426101746190195358346246762242881016710707928119020973125199597600335220176686188732073999025860 155060600538887296782517962617671450347555788381054344555539001456268680189452831160062315698482986474322296387716709989292671747 978922668181058489406663507675599642320338049377613048817085979874567772781052867215035033348050642450667612710852648837001109914 769887507004392552421783737965416800917979813137835262317794775319294801257483177741372991005066875900770459644762548438474388076 655842822437141772648037236281057239552272508379892613346840960049192531743799845858272389712078645821963027561694961956409973354 276629777068204456160534409039477757097372521171307620184694243888389707840806777932547158990704118642378158004690358831695861544 3196819133852367565049467076710376395085898875495653237178198379421129086523

e = 0x10001
 d = inverse(e, p-1) print(long_to_bytes(pow(c, d, p)))