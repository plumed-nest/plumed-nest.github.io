**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  h3/explicit/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @47 : keyword ARG is compulsory for this action
[fv-az1979-234:67285] *** Process received signal ***
[fv-az1979-234:67285] Signal: Aborted (6)
[fv-az1979-234:67285] Signal code:  (-6)
[fv-az1979-234:67285] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f32af445330]
[fv-az1979-234:67285] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f32af49eb2c]
[fv-az1979-234:67285] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f32af44527e]
[fv-az1979-234:67285] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f32af4288ff]
[fv-az1979-234:67285] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f32af8a5ff5]
[fv-az1979-234:67285] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f32af8bb0da]
[fv-az1979-234:67285] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f32af8a5a55]
[fv-az1979-234:67285] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f32af8a5a6f]
[fv-az1979-234:67285] [ 8] plumed_master(+0x146dd)[0x560f1c9e96dd]
[fv-az1979-234:67285] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f32af42a1ca]
[fv-az1979-234:67285] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f32af42a28b]
[fv-az1979-234:67285] [11] plumed_master(+0x15365)[0x560f1c9ea365]
[fv-az1979-234:67285] *** End of error message ***
</pre>
{% endraw %}
