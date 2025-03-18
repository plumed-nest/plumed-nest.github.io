**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[fv-az1267-279:64763] *** Process received signal ***
[fv-az1267-279:64763] Signal: Aborted (6)
[fv-az1267-279:64763] Signal code:  (-6)
[fv-az1267-279:64763] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3ad1a45330]
[fv-az1267-279:64763] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3ad1a9eb2c]
[fv-az1267-279:64763] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3ad1a4527e]
[fv-az1267-279:64763] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3ad1a288ff]
[fv-az1267-279:64763] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3ad1ea5ff5]
[fv-az1267-279:64763] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3ad1ebb0da]
[fv-az1267-279:64763] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3ad1ea5a55]
[fv-az1267-279:64763] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3ad1ea5a6f]
[fv-az1267-279:64763] [ 8] plumed_master(+0x146dd)[0x562516b806dd]
[fv-az1267-279:64763] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3ad1a2a1ca]
[fv-az1267-279:64763] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3ad1a2a28b]
[fv-az1267-279:64763] [11] plumed_master(+0x15365)[0x562516b81365]
[fv-az1267-279:64763] *** End of error message ***
</pre>
{% endraw %}
