**Project ID:** [plumID:20.026]({{ '/' | absolute_url }}eggs/20/026/)  
Stderr for source:  plumed_WTMD.dat   
Download: [zipped raw stdout](plumed_WTMD.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_WTMD.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @79 : keyword ARG is compulsory for this action
[fv-az1267-279:63928] *** Process received signal ***
[fv-az1267-279:63928] Signal: Aborted (6)
[fv-az1267-279:63928] Signal code:  (-6)
[fv-az1267-279:63928] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4569045330]
[fv-az1267-279:63928] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f456909eb2c]
[fv-az1267-279:63928] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f456904527e]
[fv-az1267-279:63928] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f45690288ff]
[fv-az1267-279:63928] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f45694a5ff5]
[fv-az1267-279:63928] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f45694bb0da]
[fv-az1267-279:63928] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f45694a5a55]
[fv-az1267-279:63928] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f45694a5a6f]
[fv-az1267-279:63928] [ 8] plumed_master(+0x146dd)[0x5635a24836dd]
[fv-az1267-279:63928] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f456902a1ca]
[fv-az1267-279:63928] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f456902a28b]
[fv-az1267-279:63928] [11] plumed_master(+0x15365)[0x5635a2484365]
[fv-az1267-279:63928] *** End of error message ***
</pre>
{% endraw %}
