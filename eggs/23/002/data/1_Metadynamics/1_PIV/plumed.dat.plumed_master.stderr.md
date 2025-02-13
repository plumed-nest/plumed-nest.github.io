**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/1_PIV/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[fv-az1665-105:07573] *** Process received signal ***
[fv-az1665-105:07573] Signal: Aborted (6)
[fv-az1665-105:07573] Signal code:  (-6)
[fv-az1665-105:07573] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ffb1a845330]
[fv-az1665-105:07573] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ffb1a89eb2c]
[fv-az1665-105:07573] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ffb1a84527e]
[fv-az1665-105:07573] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ffb1a8288ff]
[fv-az1665-105:07573] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ffb1aca5ff5]
[fv-az1665-105:07573] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ffb1acbb0da]
[fv-az1665-105:07573] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ffb1aca5a55]
[fv-az1665-105:07573] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ffb1aca5a6f]
[fv-az1665-105:07573] [ 8] plumed_master(+0x146dd)[0x557ed19ff6dd]
[fv-az1665-105:07573] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ffb1a82a1ca]
[fv-az1665-105:07573] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ffb1a82a28b]
[fv-az1665-105:07573] [11] plumed_master(+0x15365)[0x557ed1a00365]
[fv-az1665-105:07573] *** End of error message ***
</pre>
{% endraw %}
