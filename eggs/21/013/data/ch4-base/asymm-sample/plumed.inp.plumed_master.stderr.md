**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/asymm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @45 : keyword ARG is compulsory for this action
[fv-az1280-696:10772] *** Process received signal ***
[fv-az1280-696:10772] Signal: Aborted (6)
[fv-az1280-696:10772] Signal code:  (-6)
[fv-az1280-696:10772] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7c98045330]
[fv-az1280-696:10772] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7c9809eb2c]
[fv-az1280-696:10772] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7c9804527e]
[fv-az1280-696:10772] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7c980288ff]
[fv-az1280-696:10772] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7c984a5ff5]
[fv-az1280-696:10772] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7c984bb0da]
[fv-az1280-696:10772] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7c984a5a55]
[fv-az1280-696:10772] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7c984a5a6f]
[fv-az1280-696:10772] [ 8] plumed_master(+0x146dd)[0x55bc19d2c6dd]
[fv-az1280-696:10772] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7c9802a1ca]
[fv-az1280-696:10772] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7c9802a28b]
[fv-az1280-696:10772] [11] plumed_master(+0x15365)[0x55bc19d2d365]
[fv-az1280-696:10772] *** End of error message ***
</pre>
{% endraw %}
