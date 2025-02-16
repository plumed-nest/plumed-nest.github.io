**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/1_PIV/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[fv-az1781-845:62149] *** Process received signal ***
[fv-az1781-845:62149] Signal: Aborted (6)
[fv-az1781-845:62149] Signal code:  (-6)
[fv-az1781-845:62149] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2be1e45330]
[fv-az1781-845:62149] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2be1e9eb2c]
[fv-az1781-845:62149] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2be1e4527e]
[fv-az1781-845:62149] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2be1e288ff]
[fv-az1781-845:62149] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2be22a5ff5]
[fv-az1781-845:62149] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2be22bb0da]
[fv-az1781-845:62149] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2be22a5a55]
[fv-az1781-845:62149] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2be22a5a6f]
[fv-az1781-845:62149] [ 8] plumed_master(+0x146dd)[0x55c81c3876dd]
[fv-az1781-845:62149] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2be1e2a1ca]
[fv-az1781-845:62149] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2be1e2a28b]
[fv-az1781-845:62149] [11] plumed_master(+0x15365)[0x55c81c388365]
[fv-az1781-845:62149] *** End of error message ***
</pre>
{% endraw %}
