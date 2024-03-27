**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:986) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&, const bool&)
ERROR
I cannot understand line: HBOND_COORD SPECIES=2665-10353:4 HYDROGENS=2666-10354:4,2667-10355:4 RCUTOO=0.324 RCUTOH=0.25 ACUT=0.20pi LABEL=hb
Maybe a missing space or a typo?
[fv-az1272-890:74147] *** Process received signal ***
[fv-az1272-890:74147] Signal: Aborted (6)
[fv-az1272-890:74147] Signal code:  (-6)
[fv-az1272-890:74147] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f24e1a42520]
[fv-az1272-890:74147] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f24e1a969fc]
[fv-az1272-890:74147] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f24e1a42476]
[fv-az1272-890:74147] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f24e1a287f3]
[fv-az1272-890:74147] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f24e1ea4f26]
[fv-az1272-890:74147] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f24e1eb6d9c]
[fv-az1272-890:74147] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f24e1eb6e07]
[fv-az1272-890:74147] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f24e1eb70bb]
[fv-az1272-890:74147] [ 8] plumed_master(+0x12e7f)[0x5631f22e4e7f]
[fv-az1272-890:74147] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f24e1a29d90]
[fv-az1272-890:74147] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f24e1a29e40]
[fv-az1272-890:74147] [11] plumed_master(+0x13115)[0x5631f22e5115]
[fv-az1272-890:74147] *** End of error message ***
</pre>
{% endraw %}
