**Project ID:** [plumID:24.003]({{ '/' | absolute_url }}eggs/24/003/)  
Stderr for source:  diff_sequences/CH30/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action MOVINGRESTRAINT with label @152 : cannot find action named a0 (hint! the actions with value in this ActionSet are: d in FRET rg rg_1 rg_2 COORD PAIR phi1 phi2 phi3 phi4 phi5 phi6 phi7 phi8 phi9 phi10 phi11 phi12 phi13 phi14 phi17 phi18 phi19 phi20 phi21 phi22 phi23 phi24 phi25 phi26 phi27 phi28 phi29 phi30 psi0 psi1 psi2 psi3 psi4 psi5 psi6 psi7 psi8 psi9 psi10 psi11 psi12 psi13 psi16 psi17 psi18 psi19 psi20 psi21 psi22 psi23 psi24 psi25 psi26 psi27 psi28 psi29 omega1 omega2 omega3 omega4 omega5 omega6 omega7 omega8 omega9 omega10 omega11 omega12 omega13 omega14 omega17 omega18 omega19 omega20 omega21 omega22 omega23 omega24 omega25 omega26 omega27 omega28 omega29 omega30 chi1 chi2 chi3 chi4 chi5 chi6 chi7 chi8 chi9 chi10 chi11 chi12 chi13 chi14 chi16 chi17 chi18 chi19 chi20 chi21 chi22 chi23 chi24 chi25 chi26 chi27 chi28 chi29 chia chib chic chid chie chif chig chih chii chij chiaa chiba chifa chiga )
[fv-az1272-890:67814] *** Process received signal ***
[fv-az1272-890:67814] Signal: Aborted (6)
[fv-az1272-890:67814] Signal code:  (-6)
[fv-az1272-890:67814] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f93aac42520]
[fv-az1272-890:67814] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f93aac969fc]
[fv-az1272-890:67814] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f93aac42476]
[fv-az1272-890:67814] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f93aac287f3]
[fv-az1272-890:67814] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f93ab0a4f26]
[fv-az1272-890:67814] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f93ab0b6d9c]
[fv-az1272-890:67814] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f93ab0b6e07]
[fv-az1272-890:67814] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f93ab0b70bb]
[fv-az1272-890:67814] [ 8] plumed(+0x12f48)[0x55d9abf59f48]
[fv-az1272-890:67814] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f93aac29d90]
[fv-az1272-890:67814] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f93aac29e40]
[fv-az1272-890:67814] [11] plumed(+0x131e5)[0x55d9abf5a1e5]
[fv-az1272-890:67814] *** End of error message ***
</pre>
{% endraw %}
