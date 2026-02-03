**Project ID:** [plumID:23.016]({{ '/' | absolute_url }}eggs/23/016/)  
Stderr for source:  plumed_reweight_2D_microsw_adr_bin.dat   
Download: [zipped raw stdout](plumed_reweight_2D_microsw_adr_bin.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_2D_microsw_adr_bin.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @60 : keyword ARG is compulsory for this action
[runnervmkj6or:09223] *** Process received signal ***
[runnervmkj6or:09223] Signal: Aborted (6)
[runnervmkj6or:09223] Signal code:  (-6)
[runnervmkj6or:09223] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f04f1245330]
[runnervmkj6or:09223] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f04f129eb2c]
[runnervmkj6or:09223] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f04f124527e]
[runnervmkj6or:09223] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f04f12288ff]
[runnervmkj6or:09223] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f04f16a5ff5]
[runnervmkj6or:09223] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f04f16bb0da]
[runnervmkj6or:09223] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f04f16a5a55]
[runnervmkj6or:09223] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f04f16a5a6f]
[runnervmkj6or:09223] [ 8] plumed_master(+0x146dd)[0x55b803c806dd]
[runnervmkj6or:09223] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f04f122a1ca]
[runnervmkj6or:09223] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f04f122a28b]
[runnervmkj6or:09223] [11] plumed_master(+0x15365)[0x55b803c81365]
[runnervmkj6or:09223] *** End of error message ***
</pre>
{% endraw %}
