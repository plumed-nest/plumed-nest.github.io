**Project ID:** [plumID:24.003]({{ '/' | absolute_url }}eggs/24/003/)  
Stderr for source:  diff_sequences/CH22/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:302) void PLMD::Action::error(const string&) const
ERROR in input to action MOVINGRESTRAINT with label @220 : cannot find action named a0 (hint! the actions with value in this ActionSet are: timestep kBT posx posy posz Masses Charges Box driver p1 r1 r14 p2 r16 r30 d in FRET rg rg_1 rg_2 H1 H2 H3 H4 H5 H1_2 H2_2 H3_2 H4_2 H5_2 COORD PAIR phi1 phi2 phi3 phi4 phi5 phi6 phi7 phi8 phi9 phi10 phi13 phi14 phi15 phi16 phi17 phi18 phi19 phi20 phi21 phi22 psi0 psi1 psi2 psi3 psi4 psi5 psi6 psi7 psi8 psi9 psi12 psi13 psi14 psi15 psi16 psi17 psi18 psi19 psi20 psi21 omega1 omega2 omega3 omega4 omega5 omega6 omega7 omega8 omega9 omega10 omega13 omega14 omega15 omega16 omega17 omega18 omega19 omega20 omega21 omega22 chi1 chi2 chi3 chi4 chi5 chi6 chi7 chi8 chi9 chi10 chi12 chi13 chi14 chi15 chi16 chi17 chi18 chi19 chi20 chi21 chia chib chic chid chie chif chig chih chii chij chiaa chiba chifa chiga )
[fv-az1272-890:67790] *** Process received signal ***
[fv-az1272-890:67790] Signal: Aborted (6)
[fv-az1272-890:67790] Signal code:  (-6)
[fv-az1272-890:67790] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f65d8e42520]
[fv-az1272-890:67790] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f65d8e969fc]
[fv-az1272-890:67790] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f65d8e42476]
[fv-az1272-890:67790] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f65d8e287f3]
[fv-az1272-890:67790] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f65d92a4f26]
[fv-az1272-890:67790] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f65d92b6d9c]
[fv-az1272-890:67790] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f65d92b6e07]
[fv-az1272-890:67790] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f65d92b70bb]
[fv-az1272-890:67790] [ 8] plumed_master(+0x12e7f)[0x55e4838a7e7f]
[fv-az1272-890:67790] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f65d8e29d90]
[fv-az1272-890:67790] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f65d8e29e40]
[fv-az1272-890:67790] [11] plumed_master(+0x13115)[0x55e4838a8115]
[fv-az1272-890:67790] *** End of error message ***
</pre>
{% endraw %}
