**Project ID:** [plumID:24.003]({{ '/' | absolute_url }}eggs/24/003/)  
Stderr for source:  diff_sequences/CH22/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action MOVINGRESTRAINT with label @120 : cannot find action named a0 (hint! the actions with value in this ActionSet are: d in FRET rg rg_1 rg_2 COORD PAIR phi1 phi2 phi3 phi4 phi5 phi6 phi7 phi8 phi9 phi10 phi13 phi14 phi15 phi16 phi17 phi18 phi19 phi20 phi21 phi22 psi0 psi1 psi2 psi3 psi4 psi5 psi6 psi7 psi8 psi9 psi12 psi13 psi14 psi15 psi16 psi17 psi18 psi19 psi20 psi21 omega1 omega2 omega3 omega4 omega5 omega6 omega7 omega8 omega9 omega10 omega13 omega14 omega15 omega16 omega17 omega18 omega19 omega20 omega21 omega22 chi1 chi2 chi3 chi4 chi5 chi6 chi7 chi8 chi9 chi10 chi12 chi13 chi14 chi15 chi16 chi17 chi18 chi19 chi20 chi21 chia chib chic chid chie chif chig chih chii chij chiaa chiba chifa chiga )
[fv-az1272-890:67782] *** Process received signal ***
[fv-az1272-890:67782] Signal: Aborted (6)
[fv-az1272-890:67782] Signal code:  (-6)
[fv-az1272-890:67782] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f1e58642520]
[fv-az1272-890:67782] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f1e586969fc]
[fv-az1272-890:67782] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f1e58642476]
[fv-az1272-890:67782] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f1e586287f3]
[fv-az1272-890:67782] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f1e58aa4f26]
[fv-az1272-890:67782] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f1e58ab6d9c]
[fv-az1272-890:67782] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f1e58ab6e07]
[fv-az1272-890:67782] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f1e58ab70bb]
[fv-az1272-890:67782] [ 8] plumed(+0x12f48)[0x55ace8de8f48]
[fv-az1272-890:67782] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f1e58629d90]
[fv-az1272-890:67782] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f1e58629e40]
[fv-az1272-890:67782] [11] plumed(+0x131e5)[0x55ace8de91e5]
[fv-az1272-890:67782] *** End of error message ***
</pre>
{% endraw %}
