print(SynthDefs)
print(Samples)
print(FxList)
print(Attributes)
print(PatternMethods)
print(Scale.names())

#-------------------------------------------------------------------------



#-1,-0.8,-0.6,-0.4,-0.2,0,0.2,0.4,0.6,0.8,1
p1 >> stretch("Profecia01", dur=40, amp = 0.5, pan=[0] )
#6
v1 >> MidiOut([0],dur=4,oct=[3],amp=0.5)

p1.stop()

Clock.bpm = 65
Scale.default.set("major")
Root.default.set("F")

#0,5,1,4
v1 >> MidiOut([0],dur=4,oct=[3],amp=0.5)
#(0,6,9,11),(5,7,11,13),(1,7,10,12),(4,6,10,12)
a1 >> sinepad([(0,6,9,11)],dur=4,glide=1,oct=3,vib=1,swell=1/16,amp=0.8)

p1.stop()
v1 >> MidiOut([0,5,1,4],dur=PDur(3,8),oct=[5],amp=0.5).every(8,"stutter", 4)
a1 >> sinepad([(0,6,9,11),(5,7,11,13),(1,7,10,12),(4,6,10,12)],dur=4,glide=0.5,oct=3,vib=4,amp=0.6)
d1 >> play("V", dur=PDur(2,8),amp=0.3,lpf=900).every(8,"stutter", 4)


v1.stop()
a1 >> sinepad([(0,6,9,11)],dur=4,glide=0.5,oct=3,vib=0,amp=0.8)
d1 >> play("V", dur=4,amp=0.2,lpf=900)
f1 >> bug(dur=1,sus=3,amp=0.3)



f1.stop()
v1 >> MidiOut([0,5,1,4],dur=PDur(3,8),oct=[5]).every(2,"stutter", 8)
a1 >> sinepad([(0,6,9,11),(5,7,11,13),(1,7,10,12),(4,6,10,12)],dur=2,glide=0.5,oct=3,vib=4,amp=0.6)
d1 >> play("V", dur=PDur(3,8),amp=0.3,lpf=900).every(7,"stutter", 3)
d2 >> play("o", dur=PDur(2,8),amp=0.25,lpf=2000).every(9,"stutter", 3)
d3 >> play("--(-=):", dur=PDur(5,8),amp=0.4,pan=0.3).every(11,"stutter", 3)


p1 >> stretch("Profecia01", dur=1,slide=[0,3,-1,-4],amp = 0.150,pan=[-1,-0.8,-0.6,-0.4,-0.2,0,0.2,0.4,0.6,0.8,1] )
v1 >> MidiOut([0,5,1,4],dur=PDur(6,8),oct=[5,3,7],amp=1.2).every(3,"stutter", 8)
a1 >> sinepad([(0,6,9,11),(5,7,11,13),(1,7,10,12),(4,6,10,12)],dur=4,glide=0.5,oct=3,vib=4,amp=0.8)
a2 >> soprano([0,5,1,4],dur=PDur(2,6),amp=0.4,oct=3,pan=[-1,-0.8,-0.6,-0.4,-0.2,0,0.2,0.4,0.6,0.8,1])
d3 >> play("--(-=):", dur=PDur(3,5),amp=0.2,pan=0.3).every(7,"stutter", 3)
d1.stop()
d2.stop()

p1 >> stretch("Profecia01", dur=PDur(1,6),slide=[-10,-1,1,10], amp = 0.150,pan=[-1,-0.8,-0.6,-0.4,-0.2,0,0.2,0.4,0.6,0.8,1] )
v1 >> MidiOut([5,0,10,7,11,16],dur=PDur(2,5),amp=1.2,oct=[5,7,2])
a1 >> sinepad([(0,6,9,11),(5,7,11,13),(1,7,10,12),(4,6,10,12)],dur=2,glide=0.5,oct=3,vib=4,amp=0.8)
a2 >> soprano([5,8,10,7,11,16],dur=PDur(2,5),amp=0.3,oct=3,pan=[-1,-0.8,-0.6,-0.4,-0.2,0,0.2,0.4,0.6,0.8,1])
a3 >> bell([1,10,12,4,10,12,0,6,11],dur=PDur(3,4),oct=5,amp=0.05,pan=[1,0.8,0.6,0.4,0.2,0,-0.2,-0.4,-0.6,-0.8,-1],slide=[0,0,-2,8]).every(4,"stutter", 3).every(3,"stutter", 2).every(2,"stutter", 6)
a4 >> star([1,4,0],dur=PDur(3,6),oct=5,amp=0.05,tremolo=1).every(4,"stutter", 3).every(3,"stutter", 2).every(2,"stutter", 6)
d1 >> play("V", dur=PDur(3,8),amp=0.3,lpf=1000).every(7,"stutter", 3)
d2 >> play("o", dur=PDur(2,8),amp=0.25,lpf=2000).every(9,"stutter", 3)
d3 >> play("--(-=):", dur=PDur(3,5),amp=0.4,pan=0.3).every(11,"stutter", 3)


p1 >> stretch("Profecia01", dur=PDur(6,6),slide=[-10,2,10,0,-4], amp = 0.2,pan=[-1,-0.8,-0.6,-0.4,-0.2,0,0.2,0.4,0.6,0.8,1] )
v1 >> MidiOut([0,5,1,4],dur=4,oct=[5],amp=0.5)
a3.stop()
d1.stop()
d2.stop()
d3.stop()


a2.stop()
p1.stop()

v1.stop()

a1.stop()
a4.stop()
p1 >> stretch("Profecia02", dur=30, amp = 0.280, slide=[0],pan=[0] )
v1 >> MidiOut([0],dur=2,oct=[2],amp=2)
Clock.bpm = 70
Scale.default.set("phrygian")
Root.default.set("F")
#0,2,4,6,8,10,11,13

p1.stop()
v1 >> MidiOut([0,2,4,6,8,10,11,13],dur=2,oct=[2],amp=2)
#0,2,4,6,8,10,11,13
a1 >> razz([0,2,4,6,8,10,11,13],dur=4,amp=0.5,oct=3)


p1 >> stretch("Profecia02", dur=1, amp = 0.05, slide=[0,0,-2,1,0,-2,-5,-10,2,0],pan=[-1,-0.8,-0.6,-0.4,-0.2,0,0.2,0.4,0.6,0.8,1] )
v1 >> MidiOut([0,13],dur=4,oct=[2],amp=2)
a1 >> razz([0,2,4,6,8,10,11,13],dur=8,amp=0.5,oct=3)
a2 >> swell([0,2,4,6,8,10,11,13],dur=8,amp=0.5,oct=3,sus=18)

p1 >> stretch("Profecia02", dur=1/3, amp = 0.09, slide=[-0.5,0,-2,1,0,-2,-5,-10,2,0],pan=[-1,-0.8,-0.6,-0.4,-0.2,0,0.2,0.4,0.6,0.8,1] )
v1 >> MidiOut([0],dur=PDur(3,5),oct=[3],amp=1)
a1 >> razz([0,2,4,6,8,10,11,13],dur=16,amp=0.5,oct=3)
a2 >> swell([0,2,4,6,8,10,11,13],dur=16,amp=0.5,oct=3,sus=18)
a3 >> charm([0,2,4,6,8,10,11],dur=PDur(3,16),amp=[0.2,0.3,0.1,0.4,0.2],oct=5)
a4 >> snick([0,2,4,6,8,10,11,13],dur=PDur(3,5),amp=[0.5,0.2,0.4,0.1,0.4],oct=5)

p1 >> stretch("Profecia02", dur=PDur(3,8), amp = 0.08, slide=[0,0,-2,1,0,-2,-5,-10,2,0,6,12,-20],pan=[-1,-0.8,-0.6,-0.4,-0.2,0,0.2,0.4,0.6,0.8,1] )
v1 >> MidiOut([0,2,4,6,8,10,11,13],dur=PDur(3,5),oct=[3],amp=1)
a1 >> razz([0,2,4,6,8,10,11,13],dur=16,amp=0.5,oct=3)
a2 >> swell([0,2,4,6,8,10,11,13],dur=16,amp=0.5,oct=3,sus=18)
a3 >> charm([0,2,4,6,8,10,11],dur=PDur(3,16),amp=[0.2,0.3,0.1,0.4,0.2],oct=5,pan=[1,0.5,0,-0.5,-1])
a4 >> snick([0,2,4,6,8,10,11,13],dur=PDur(3,5),amp=[0.5,0.2,0.4,0.1,0.4],oct=5)
a5 >> spark([0,2,4,6,8,10,11,13],dur=PDur(5,6),amp=[0.05,0.09,0.07,0.09,0.06],oct=5,pan=[-1,-0.5,0,0.5,1])
a6 >> arpy([0,2,4,6,8,10,11,13],dur=PDur(3,6),amp=[0.4,0.2,0.3,0.9,0.1],oct=2).every(4,"stutter", 3)
a7 >> gong([0,2,4,6,8,10,11,13],dur=PDur(2,5),amp=[0.4,0.2,0.3,0.9,0.1],oct=4,pan=[-1,-0.5,0,0.5,1]).every(4,"stutter", 2)


d1 >> play("qn", dur=PDur(3,7),amp=0.17,sample=[1,2,3,4,5],pan= (-1)).every(11,"stutter", 3)
d2 >> play("nq", dur=PDur(4,7),amp=0.17,sample=[1,2,3,4,5],pan=(1)).every(13,"stutter", 6)

d3 >> play("u@", dur=PDur(5,7),amp=0.15,sample=[1,2,3,4,5],pan=[1,0.8,0.6,0.4,0.2,0,-0.2,-0.4,-0.6,-0.8,-1]).every(15,"stutter", 8)
d4 >> play("jJ", dur=PDur(4,6),amp=0.09,sample=[1,2,3,4,5,6,7],pan=[-1,-0.8,-0.6,-0.4,-0.2,0,0.2,0.4,0.6,0.8,1]).every(13,"stutter", 6)



d5 >> play("V", dur=1,amp=0.3,sample=[1,2,3,4,5]).every(4,"stutter", 3)


v1 >> MidiOut([0,2,4,6,8,10,11,13],dur=PDur(3,6),oct=[6],amp=1).every(4,"stutter", 3)
d1 >> play("qn", dur=PDur(3,5),amp=0.05,sample=[1,2,3,4,5],pan= (1)).every(11,"stutter", 3)
d2 >> play("nq", dur=PDur(4,6),amp=0.05,sample=[1,2,3,4,5],pan= (-1)).every(13,"stutter", 6)
d3 >> play("u@", dur=PDur(5,8),amp=0.03,sample=[1,2,3,4,5],pan=[1,0.8,0.6,0.4,0.2,0,-0.2,-0.4,-0.6,-0.8,-1]).every(15,"stutter", 3)
d4 >> play("j", dur=PDur(4,5),amp=0.07,sample=[1,2,3,4,5,6,7],pan=[-1,-0.8,-0.6,-0.4,-0.2,0,0.2,0.4,0.6,0.8,1]).every(13,"stutter", 6)
d5 >> play("V", dur=PDur(3,6),amp=0.3,sample=[1,2,3,4,5]).every(4,"stutter", 3)#.every(2,"stutter", 4)


v1 >> MidiOut([0,2,4,6,8,10,11,13],dur=PDur(5,6),oct=[6,1,7,3,8,2],amp=1).every(4,"stutter", 3)a3 >> charm([0,2,4,6,8,10,11],dur=PDur(3,6),amp=[0.2,0.3,0.1,0.4,0.2],oct=5,pan=[-1,-0.5,0,0.5,1])
a4 >> snick([0,2,4,6,8,10,11,13],dur=PDur(4,5),amp=[0.7,0.2,0.4,0.1,0.4],oct=5)
a5 >> spark([0,2,4,6,8,10,11,13],dur=PDur(3,8),amp=[0.07,0.09,0.07,0.09,0.06],oct=5,pan=[-1,-0.5,0,0.5,1])
a6 >> arpy([0,2,4,6,8,10,11,13],dur=PDur(3,5),amp=[0.4,0.2,0.3,0.9,0.1],oct=2).every(4,"stutter", 3)
a7 >> gong([0,2,4,6,8,10,11,13],dur=PDur(3,7),amp=[0.4,0.2,0.3,0.9,0.1],oct=4,pan=[-1,-0.5,0,0.5,1]).every(4,"stutter", 2)
d5 >> play("V", dur=PDur(3,8),amp=0.3,sample=[1,2,3,4,5]).every(4,"stutter", 3)


p1 >> stretch("Profecia03", dur=20, amp = 0.250, slide=[0],pan=[0] )
a1.stop()
a2.stop()
a3.stop()
a4.stop()
a5.stop()
a6.stop()
a7.stop()
d1.stop()
d2.stop()
d3.stop()
d4.stop()
d5.stop()
v1 >> MidiOut([0,2,4,6,8,10,11,13],dur=PDur(3,5),oct=[6],amp=1.5).every(4,"stutter", 3)

v1.stop()



v1 >> MidiOut([1,10,12,4,10,12,0,6,11],dur=8,oct=[1],amp=1).every(4,"stutter", 3)
Clock.bpm = 85
Scale.default.set("minMaj")
Root.default.set("D")
p1 >> stretch("Profecia04", dur=PDur(2,7), amp = 0.07, pan=[-1,-0.8,-0.6,-0.4,-0.2,0,0.2,0.4,0.6,0.8,1] )
#dur=PDur(1,7)

p2 >> stretch("Profecia05", dur=44, amp = 0.17, pan=[0] )
p1.stop()

p2.stop()
v1 >> MidiOut([1,10,12,4,10,12,0,6,11],dur=PDur(1,8),oct=[2],amp=1).every(4,"stutter", 3)
a1 >> pads([(0,6,9,11),(5,7,11,13),(1,7,10,12),(4,6,10,12)],dur=4,glide=2,oct=3,chop=8,vib=1,amp=0.38)
d1 >> play("V", dur=PDur(1,8),amp=0.35,lpf=600)
d2 >> play("o", dur=PDur(2,8),amp=0.33,lpf=2000)
d3 >> play("--(-=):", dur=PDur(5,7),amp=0.32).every(11,"stutter", 3)


p2.stop()
a1 >> pads([(0,6,9,11),(5,7,11,13),(1,7,10,12),(4,6,10,12)],dur=4,glide=2,oct=3,chop=2,vib=1,amp=0.6)
d1 >> play("V", dur=PDur(3,8),amp=0.33,lpf=600).every(8,"stutter", 4)
d2 >> play("o", dur=PDur(6,8),amp=0.3,lpf=2000)


p2 >> stretch("Profecia05 ", dur=PDur(4,8), amp = 0.1, pan=[-1,-0.8,-0.6,-0.4,-0.2,0,0.2,0.4,0.6,0.8,1] )
p1 >> stretch("Profecia06", dur=40, amp = 0.25, pan=[0] )
d2.stop()
d3.stop()
#dur=[1/3,1/2,1/3]
a1 >> pads([(0,6,9,11),(5,7,11,13),(1,7,10,12),(4,6,10,12)],dur=4,glide=2,oct=3,chop=1,vib=2,amp=0.6)
d1 >> play("V", dur=[1/2,1/2,1/3],amp=0.38,lpf=600).every(11,"stutter", 3)
f1 >> ambi(dur=1,sus=3,amp=0.5)


p2.stop()
p1 >> stretch("Profecia06", dur=PDur(1,8), amp = 0.2, pan=[-1,-0.8,-0.6,-0.4,-0.2,0,0.2,0.4,0.6,0.8,1] )
f1.stop()
a1 >> pads([(0,6,9,11),(5,7,11,13),(1,7,10,12),(4,6,10,12)],dur=2,glide=0.5,oct=3,vib=16,amp=0.5,lpf=4000)
d1 >> play("V", dur=PDur(3,8),amp=0.4,lpf=600).every(7,"stutter", 3)
d2 >> play("o", dur=PDur(2,8),amp=0.3,lpf=2000).every(9,"stutter", 3)
d3 >> play("--(-=):", dur=PDur(5,8),amp=0.3).every(11,"stutter", 3)


p1.stop()
v1 >> MidiOut([0,5,1,4],dur=PDur(2,6),oct=[2],amp=1).every(4,"stutter", 3)
a1 >> sinepad([(0,6,9,11),(5,7,11,13),(1,7,10,12),(4,6,10,12)],dur=4,glide=0.5,oct=3,vib=4,amp=0.8,lpf=4000)
a2 >> soprano([0,5,1,4],dur=PDur(2,6),amp=0.2,oct=3)
d3 >> play("--(-=):", dur=PDur(3,5),amp=0.2).every(11,"stutter", 3)
d1.stop()
d2.stop()


v1 >> MidiOut([1,4,0],dur=PDur(3,5),oct=[2],amp=1).every(4,"stutter", 3)
a1 >> sinepad([(0,6,9,11),(5,7,11,13),(1,7,10,12),(4,6,10,12)],dur=2,glide=0.5,oct=3,vib=4,amp=0.5)
a2 >> soprano([0,5,1,4],dur=PDur(2,5),amp=0.2,oct=3).every(11,"stutter", 3)
a3 >> bell([1,10,12,4,10,12,0,6,11],dur=PDur(3,4),oct=5,amp=0.02).every(4,"stutter", 3).every(3,"stutter", 2).every(2,"stutter", 6)
a4 >> star([1,4,0],dur=PDur(3,4),oct=5,amp=0.05,tremolo=1).every(4,"stutter", 3).every(3,"stutter", 2).every(2,"stutter", 6)
d1 >> play("V", dur=PDur(3,8),amp=0.4,lpf=600).every(7,"stutter", 3)
d2 >> play("o", dur=PDur(2,8),amp=0.3,lpf=2000).every(9,"stutter", 3)
d3 >> play("--(-=):", dur=PDur(3,5),amp=0.2).every(11,"stutter", 3)


p2 >> stretch("Profecia06 ", dur=PDur(6,8), amp = 0.09, pan=[-1,-0.8,-0.6,-0.4,-0.2,0,0.2,0.4,0.6,0.8,1] )
p1 >> stretch("Profecia07", dur=40, amp = 0.18, pan=[0] )
v1 >> MidiOut([0,5,1,4],dur=PDur(3,5),oct=[2],amp=1).every(4,"stutter", 3)
d2.stop()
d3.stop()
a1 >> pads([(0,6,9,11),(5,7,11,13),(1,7,10,12),(4,6,10,12)],dur=4,glide=2,oct=3,chop=1,vib=2,amp=0.3)
d1 >> play("V", dur=1/6,amp=0.4,lpf=600)
f1 >> ambi(dur=1,sus=3,amp=0.2)


p1 >> stretch("Profecia07", dur=PDur(1,30), amp = 0.150, pan=[-1,-0.8,-0.6,-0.4,-0.2,0,0.2,0.4,0.6,0.8,1] )
p2.stop()
a3.stop()
d1.stop()
d2.stop()
d3.stop()
a2.stop()


d2.stop()
d3.stop()
a1.stop()
a4.stop()
a1 >> pads([(0,6,9,11),(5,7,11,13),(1,7,10,12),(4,6,10,12)],dur=4,glide=2,oct=3,chop=1,vib=2,amp=0.3)
d1 >> play("V", dur=1/3,amp=0.4,lpf=600)
f1 >> ambi(dur=1,sus=3,amp=0.2)

p1.stop()
a1.stop()
a4.stop()
f1.stop()
d1.stop()




v1 >> MidiOut([0,2,4,6,8,10,11,13],dur=2,oct=[4,3,5],amp=1).every(4,"stutter", 3)
Clock.bpm = 90
Scale.default.set("lydianAug")
Root.default.set("A")

p1.stop()
a1 >> growl([0,2,4,6,8,10,11,13],dur=4,amp=0.3,oct=3)


a2 >> space([0,2,4,6,8,10,11,13],dur=8,amp=0.2,oct=3,sus=18,vib=3)


a3 >> bell([0,2,4,6,8,10,11],dur=PDur(3,16),amp=[0.08,0.07,0.05,0.06,0.04],oct=5)
a4 >> space([0,2,4,6,8,10,11,13],dur=PDur(3,5),amp=[0.05,0.02,0.04,0.01,0.04],oct=8)


v1 >> MidiOut([0,2,4,6,8,10,11,13],dur=PDur(5,6),oct=[4,3,5],amp=1).every(2,"stutter", 3)
a1 >> growl([0,2,4,6,8,10,11,13],dur=PDur(3,6),amp=0.2,oct=3)
a2 >> space([0,2,4,6,8,10,11,13],dur=4,amp=0.2,oct=3,sus=18)
a3 >> bell([0,2,4,6,8,10,11],dur=PDur(3,16),amp=[0.05,0.09,0.07,0.09,0.06],oct=5)
a4 >> space([0,2,4,6,8,10,11,13],dur=PDur(3,8),amp=[0.08,0.07,0.05,0.06,0.04],oct=8,pan=[-1,-0.8,-0.6,-0.4,-0.2,0,0.2,0.4,0.6,0.8,1])
a5 >> bell([0,2,4,6,8,10,11,13],dur=PDur(5,6),amp=[0.05,0.09,0.07,0.09,0.06],oct=5,pan=[1,0.8,0.6,0.4,0.2,0,-0.2,-0.4,-0.6,-0.8,-1])
a6 >> bell([0,2,4,6,8,10,11,13],dur=PDur(3,6),amp=[0.04,0.02,0.03,0.09,0.1],oct=2,pan=[-1,-0.8,-0.6,-0.4,-0.2,0,0.2,0.4,0.6,0.8,1]).every(4,"stutter", 3)
a7 >> space([0,2,4,6,8,10,11,13],dur=PDur(2,5),amp=[0.05,0.09,0.07,0.09,0.06],oct=4,pan=[1,0.8,0.6,0.4,0.2,0,-0.2,-0.4,-0.6,-0.8,-1]).every(4,"stutter", 2)


d1 >> play("---(==-)", dur=PDur(6,8),amp=0.2,sample=[1,2,3,4,5]).every(11,"stutter", 16)
d2 >> play("o.o.", dur=PDur(3,4),amp=0.3,sample=[1,2,3,4,5]).every(13,"stutter", 6)
d3 >> play("cc$%&", dur=PDur(2,8),amp=0.2,sample=[1,2,3,4,5]).every(15,"stutter", 3)
d4 >> play("V", dur=PDur(3,8),amp=0.4,sample=[1,2,3,4,5,6,7]).every(8,"stutter", 3)


d4 >> play("V", dur=1/3,amp=0.4,sample=[1,2,3,4,5]).every(4,"stutter", 3)


d1 >> play("---(==-)", dur=PDur(3,8),amp=0.2,sample=[1,2,3,4,5]).every(8,"stutter", 12)
d2 >> play("o.o.", dur=PDur(3,4),amp=0.3,sample=[1,2,3,4,5]).every(13,"stutter", 6)
d3 >> play("cc$%&", dur=PDur(3,8),amp=0.3,sample=[1,2,3,4,5]).every(15,"stutter", 3)
d4 >> play("V", dur=PDur(3,8),amp=0.4,sample=[1,2,3,4,5,6,7]).every(4,"stutter", 4)


a1 >> growl([0,2,4,6,8,10,11,13],dur=PDur(3,8),amp=0.2,oct=3)
a2 >> space([0,2,4,6,8,10,11,13],dur=4,amp=0.2,oct=3,sus=18)
a3 >> bell([0,2,4,6,8,10,11],dur=PDur(6,12),amp=[0.05,0.09,0.07,0.09,0.06],oct=5,pan=[-1,-0.8,-0.6,-0.4,-0.2,0,0.2,0.4,0.6,0.8,1])
a4 >> space([0,2,4,6,8,10,11,13],dur=PDur(3,8),amp=[0.08,0.07,0.05,0.06,0.04],oct=8)
a5 >> bell([0,2,4,6,8,10,11,13],dur=PDur(6,8),amp=[0.05,0.09,0.07,0.09,0.06],oct=5,pan=[1,0.8,0.6,0.4,0.2,0,-0.2,-0.4,-0.6,-0.8,-1])
a6 >> ambi([0,2,4,6,8,10,11,13],dur=PDur(3,8),amp=[0.04,0.02,0.03,0.09,0.1],oct=2).every(4,"stutter", 3)
a7 >> space([0,2,4,6,8,10,11,13],dur=PDur(2,8),amp=[0.05,0.09,0.07,0.09,0.06],oct=4).every(4,"stutter", 2)
d4 >> play("V", dur=PDur(3,8),amp=0.4,sample=[1,2,3,4,5]).every(4,"stutter", 3)


p1 >> stretch("Profecia08", dur=74, amp = 0.190, pan=[0] )
a1 >> growl([0,2,4,6,8,10,11,13],dur=4,amp=0.3,oct=3, pan=[0.1])
a2 >> space([0,2,4,6,8,10,11,13],dur=8,amp=0.3,oct=3,sus=18,vib=3, pan=[-0.1])
v1 >> MidiOut([0,2,4,6,8,10,11,13],dur=8,oct=[1,2,1],amp=1).every(2,"stutter", 3)
a3.stop()
a4.stop()
a5.stop()
a6.stop()
a7.stop()
d1.stop()
d2.stop()
d3.stop()
d5.stop()
d4.stop()

a1.stop()
a2.stop()

p1.stop()

p1 >> stretch("despedida", dur=68, amp = 1, pan=[0] )

p1.stop()

v1.stop()


Gracias !!
