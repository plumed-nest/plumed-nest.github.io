**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: HBOND_COORD SPECIES=2665-10353:4 HYDROGENS=2666-10354:4,2667-10355:4 RCUTOO=0.324 RCUTOH=0.25 ACUT=0.20pi LABEL=hb
Maybe a missing space or a typo?
[fv-az1771-923:10508] *** Process received signal ***
[fv-az1771-923:10508] Signal: Aborted (6)
[fv-az1771-923:10508] Signal code:  (-6)
[fv-az1771-923:10508] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f209c442520]
[fv-az1771-923:10508] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f209c4969fc]
[fv-az1771-923:10508] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f209c442476]
[fv-az1771-923:10508] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f209c4287f3]
[fv-az1771-923:10508] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f209c8a2b9e]
[fv-az1771-923:10508] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f209c8ae20c]
[fv-az1771-923:10508] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f209c8ae277]
[fv-az1771-923:10508] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f209c8ae52b]
[fv-az1771-923:10508] [ 8] plumed(+0x12f48)[0x5576d0c3bf48]
[fv-az1771-923:10508] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f209c429d90]
[fv-az1771-923:10508] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f209c429e40]
[fv-az1771-923:10508] [11] plumed(+0x131e5)[0x5576d0c3c1e5]
[fv-az1771-923:10508] *** End of error message ***
</pre>
{% endraw %}
