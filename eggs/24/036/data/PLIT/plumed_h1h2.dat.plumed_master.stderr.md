**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT/plumed_h1h2.dat   
Download: [zipped raw stdout](plumed_h1h2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_h1h2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @49 : keyword ARG is compulsory for this action
[fv-az1374-136:61269] *** Process received signal ***
[fv-az1374-136:61269] Signal: Aborted (6)
[fv-az1374-136:61269] Signal code:  (-6)
[fv-az1374-136:61269] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0634445330]
[fv-az1374-136:61269] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f063449eb2c]
[fv-az1374-136:61269] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f063444527e]
[fv-az1374-136:61269] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f06344288ff]
[fv-az1374-136:61269] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f06348a5ff5]
[fv-az1374-136:61269] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f06348bb0da]
[fv-az1374-136:61269] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f06348a5a55]
[fv-az1374-136:61269] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f06348a5a6f]
[fv-az1374-136:61269] [ 8] plumed_master(+0x146dd)[0x55ac6dedb6dd]
[fv-az1374-136:61269] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f063442a1ca]
[fv-az1374-136:61269] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f063442a28b]
[fv-az1374-136:61269] [11] plumed_master(+0x15365)[0x55ac6dedc365]
[fv-az1374-136:61269] *** End of error message ***
</pre>
{% endraw %}
