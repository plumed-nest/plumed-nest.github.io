**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/metad/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @52 : keyword ARG is compulsory for this action
[fv-az1440-40:64512] *** Process received signal ***
[fv-az1440-40:64512] Signal: Aborted (6)
[fv-az1440-40:64512] Signal code:  (-6)
[fv-az1440-40:64512] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f221ca45330]
[fv-az1440-40:64512] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f221ca9eb2c]
[fv-az1440-40:64512] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f221ca4527e]
[fv-az1440-40:64512] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f221ca288ff]
[fv-az1440-40:64512] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f221cea5ff5]
[fv-az1440-40:64512] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f221cebb0da]
[fv-az1440-40:64512] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f221cea5a55]
[fv-az1440-40:64512] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f221cea5a6f]
[fv-az1440-40:64512] [ 8] plumed_master(+0x146dd)[0x55d1570d76dd]
[fv-az1440-40:64512] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f221ca2a1ca]
[fv-az1440-40:64512] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f221ca2a28b]
[fv-az1440-40:64512] [11] plumed_master(+0x15365)[0x55d1570d8365]
[fv-az1440-40:64512] *** End of error message ***
</pre>
{% endraw %}
