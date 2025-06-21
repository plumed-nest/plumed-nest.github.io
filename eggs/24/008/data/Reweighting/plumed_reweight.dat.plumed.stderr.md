**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[pkrvmxyh4eaekms:07740] *** Process received signal ***
[pkrvmxyh4eaekms:07740] Signal: Aborted (6)
[pkrvmxyh4eaekms:07740] Signal code:  (-6)
[pkrvmxyh4eaekms:07740] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd535045330]
[pkrvmxyh4eaekms:07740] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd53509eb2c]
[pkrvmxyh4eaekms:07740] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd53504527e]
[pkrvmxyh4eaekms:07740] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd5350288ff]
[pkrvmxyh4eaekms:07740] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd5354a5ff5]
[pkrvmxyh4eaekms:07740] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd5354bb0da]
[pkrvmxyh4eaekms:07740] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd5354a5a55]
[pkrvmxyh4eaekms:07740] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd5354a5a6f]
[pkrvmxyh4eaekms:07740] [ 8] plumed(+0x146dd)[0x55870889d6dd]
[pkrvmxyh4eaekms:07740] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd53502a1ca]
[pkrvmxyh4eaekms:07740] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd53502a28b]
[pkrvmxyh4eaekms:07740] [11] plumed(+0x15365)[0x55870889e365]
[pkrvmxyh4eaekms:07740] *** End of error message ***
</pre>
{% endraw %}
