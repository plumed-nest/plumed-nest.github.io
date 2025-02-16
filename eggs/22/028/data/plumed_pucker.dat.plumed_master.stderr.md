**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[fv-az1665-105:62077] *** Process received signal ***
[fv-az1665-105:62077] Signal: Aborted (6)
[fv-az1665-105:62077] Signal code:  (-6)
[fv-az1665-105:62077] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb94a845330]
[fv-az1665-105:62077] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb94a89eb2c]
[fv-az1665-105:62077] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb94a84527e]
[fv-az1665-105:62077] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb94a8288ff]
[fv-az1665-105:62077] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb94aca5ff5]
[fv-az1665-105:62077] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb94acbb0da]
[fv-az1665-105:62077] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb94aca5a55]
[fv-az1665-105:62077] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb94aca5a6f]
[fv-az1665-105:62077] [ 8] plumed_master(+0x146dd)[0x5600da13e6dd]
[fv-az1665-105:62077] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb94a82a1ca]
[fv-az1665-105:62077] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb94a82a28b]
[fv-az1665-105:62077] [11] plumed_master(+0x15365)[0x5600da13f365]
[fv-az1665-105:62077] *** End of error message ***
</pre>
{% endraw %}
