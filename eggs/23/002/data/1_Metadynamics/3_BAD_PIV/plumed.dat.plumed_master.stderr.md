**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/3_BAD_PIV/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[fv-az1781-845:61993] *** Process received signal ***
[fv-az1781-845:61993] Signal: Aborted (6)
[fv-az1781-845:61993] Signal code:  (-6)
[fv-az1781-845:61993] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3911645330]
[fv-az1781-845:61993] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f391169eb2c]
[fv-az1781-845:61993] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f391164527e]
[fv-az1781-845:61993] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f39116288ff]
[fv-az1781-845:61993] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3911aa5ff5]
[fv-az1781-845:61993] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3911abb0da]
[fv-az1781-845:61993] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3911aa5a55]
[fv-az1781-845:61993] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3911aa5a6f]
[fv-az1781-845:61993] [ 8] plumed_master(+0x146dd)[0x55d8c2d446dd]
[fv-az1781-845:61993] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f391162a1ca]
[fv-az1781-845:61993] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f391162a28b]
[fv-az1781-845:61993] [11] plumed_master(+0x15365)[0x55d8c2d45365]
[fv-az1781-845:61993] *** End of error message ***
</pre>
{% endraw %}
