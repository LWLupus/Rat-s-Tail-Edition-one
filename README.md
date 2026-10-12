# Rat's Tail Edition One
It is just a one line DATA URI of a mouse trail.
Here is a preview:
![GiFz](https://user-cdn.hackclub-assets.com/01a12d6d-dc2c-7faa-a073-7053a99447e5/ezgif-6f5f76d8899b950d.gif)
![PiC](https://cdn.hackclub.com/01a12d6d-cb8e-7d2b-9231-d491c19fcaec/Screenshot_44.png)
## HOW THIS WAS MADE
This was made with just html.

## heres how to run the project

Run This pre converted code

```
data:text/html;charset=utf-8,%3C!DOCTYPE%20html%3E%3Chtml%3E%3Chead%3E%3Cmeta%20charset%3Dutf-8%3E%3Ctitle%3ERat's%20Tail%3C%2Ftitle%3E%3Cstyle%3Ehtml%2Cbody%7Bmargin%3A0%3Bheight%3A100%25%3Bbackground%3A%230a0a0f%3Boverflow%3Ahidden%3Bcursor%3Anone%7Dcanvas%7Bdisplay%3Ablock%7D%3C%2Fstyle%3E%3C%2Fhead%3E%3Cbody%3E%3Ccanvas%20id%3Dc%3E%3C%2Fcanvas%3E%3Cscript%3E(()%3D%3E%7Bconst%20x%3Dc.getContext%602d%60%2CP%3D%5B%5D%3Blet%20W%2CH%2Cpx%3D0%2Cpy%3D0%2Cmx%3D0%2Cmy%3D0%2Ch%3D190%2CS%3D0%2CA%2CV%2CN%3Bconst%20R%3D()%3D%3E%7Bc.width%3DW%3DinnerWidth%3Bc.height%3DH%3DinnerHeight%7D%3Bonresize%3DR%3BR()%3Bpx%3Dmx%3DinnerWidth%2F2%3Bpy%3Dmy%3DinnerHeight%2F2%3Bconst%20K%3Do%3D%3E%60hsl(%24%7Bh%2Bo%7D%20100%25%2060%25)%60%2Cu%3D(X%2CY%2Cv%2Cw%2Cr%2Ce%2CD%2Co%3D0)%3D%3EP.push(%7Bx%3AX%2Cy%3AY%2Cvx%3Av%2Cvy%3Aw%2Cr%2Ca%3Ae%2Cd%3AD%2Cc%3AK(o)%7D)%3Bconst%20B%3D(n%2Cv%2Co)%3D%3E%7Bfor(let%20i%3D0%3Bi%3Cn%3Bi%2B%2B)%7Bconst%20a%3DMath.random()*7%2Cq%3Dv*(.3%2BMath.random())%3Bu(mx%2BMath.cos(a)*6%2Cmy%2BMath.sin(a)*6%2CMath.cos(a)*q%2CMath.sin(a)*q%2C1%2BMath.random()*3.5%2C1%2C.04%2C(Math.random()-.5)*o)%7D%7D%2Cau%3D()%3D%3E%7Bif(A)return%3BA%3Dnew%20AudioContext%3BA.resume()%3Bconst%20L%3DA.sampleRate*2%3BN%3DA.createBuffer(1%2CL%2CA.sampleRate)%3Bconst%20d%3DN.getChannelData(0)%3Blet%20b0%3D0%2Cb1%3D0%2Cb2%3D0%2Cb3%3D0%2Cb4%3D0%2Cb5%3D0%2Cb6%3D0%3Bfor(let%20i%3D0%3Bi%3CL%3Bi%2B%2B)%7Bconst%20w%3DMath.random()*2-1%3Bb0%3D.99886*b0%2Bw*.0555179%3Bb1%3D.99332*b1%2Bw*.0750759%3Bb2%3D.969*b2%2Bw*.153852%3Bb3%3D.8665*b3%2Bw*.3104856%3Bb4%3D.55*b4%2Bw*.5329522%3Bb5%3D-.7616*b5-w*.016898%3Bd%5Bi%5D%3D(b0%2Bb1%2Bb2%2Bb3%2Bb4%2Bb5%2Bb6%2Bw*.5362)*.11%3Bb6%3Dw*.115926%7Dconst%20s%3DA.createBufferSource()%3Bs.buffer%3DN%3Bs.loop%3D!0%3Bconst%20F%3DA.createBiquadFilter()%3BF.type%3D'bandpass'%3BF.frequency.value%3D700%3BF.Q.value%3D.9%3BV%3DA.createGain()%3BV.gain.value%3D1e-4%3Bs.connect(F).connect(V).connect(A.destination)%3Bs.start()%7D%2CG%3Dv%3D%3E%7Bau()%3BA.resume()%3Bconst%20n%3DA.currentTime%2Cs%3DA.createBufferSource()%2Cf%3DA.createBiquadFilter()%2Cg%3DA.createGain()%3Bs.buffer%3DN%3Bf.type%3D'bandpass'%3Bf.frequency.value%3D2500%3Bf.frequency.exponentialRampToValueAtTime(150%2Cn%2B.5)%3Bg.gain.value%3D1e-4%3Bg.gain.exponentialRampToValueAtTime(v%2Cn%2B.03)%3Bg.gain.exponentialRampToValueAtTime(1e-4%2Cn%2B.58)%3Bs.connect(f).connect(g).connect(A.destination)%3Bs.start(n%2C1.3*Math.random())%3Bs.stop(n%2B.6)%7D%3Bonmousemove%3De%3D%3E%7Bmx%3De.clientX%3Bmy%3De.clientY%3Bau()%7D%3Bonmousedown%3De%3D%3E%7Bau()%3BA.resume()%3Be.button%3Fe.button%3D%3D2%26%26(h%3D(h%2B50)%25360%2CB(40%2C6%2C90)%2CG(.5))%3A(B(90%2C9%2C70)%2CG(1))%3Be.preventDefault()%7D%3Boncontextmenu%3De%3D%3Ee.preventDefault()%3Bconst%20loop%3D()%3D%3E%7Bconst%20dx%3Dmx-px%2Cdy%3Dmy-py%2Cd%3DMath.hypot(dx%2Cdy)%3BS%2B%3D(d-S)*.25%3Bx.fillStyle%3D'rgba(0%2C0%2C0%2C.1)'%3Bx.fillRect(0%2C0%2CW%2CH)%3Bconst%20n%3DMath.max(1%2CMath.ceil(d%2F6))%3Bfor(let%20i%3D1%3Bi%3C%3Dn%3Bi%2B%2B)u(px%2Bdx*i%2Fn%2Cpy%2Bdy*i%2Fn%2C(Math.random()-.5)*.6%2C(Math.random()-.5)*.6%2C1%2BMath.random()*2%2C1%2C.02)%3Bpx%3Dmx%3Bpy%3Dmy%3Bfor(let%20i%3DP.length-1%3Bi%3E%3D0%3Bi--)%7Bconst%20p%3DP%5Bi%5D%3Bp.x%2B%3Dp.vx%3Bp.y%2B%3Dp.vy%3Bp.vx*%3D.97%3Bp.vy*%3D.97%3Bif((p.a-%3Dp.d)%3E0)%7Bx.globalAlpha%3Dp.a%3Bx.fillStyle%3Dp.c%3Bx.beginPath()%3Bx.arc(p.x%2Cp.y%2Cp.r%2C0%2C7)%3Bx.fill()%7Delse%20P.splice(i%2C1)%7Dx.globalAlpha%3D1%3BV%26%26V.gain.setTargetAtTime(1e-4%2BMath.min(1%2CS%2F60)**1.4*.22%2CA.currentTime%2C.06)%3BrequestAnimationFrame(loop)%7D%3BrequestAnimationFrame(loop)%7D)()%3B%3C%2Fscript%3E%3C%2Fbody%3E%3C%2Fhtml%3E
```
!!!Click for the sounds to start working!!!

OR. Download the Html and the converter and convert it trough the converter
```sh
git clone https://github.com/LWLupus/Rat-s-Tail-Edition-oner.git
```

Always like Ratzz

## AI DISCLOSURE
Helped with the math.
