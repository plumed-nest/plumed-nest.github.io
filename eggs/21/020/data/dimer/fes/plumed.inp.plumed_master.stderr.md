**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  dimer/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @40 : keyword ARG is compulsory for this action
[fv-az1267-279:67104] *** Process received signal ***
[fv-az1267-279:67104] Signal: Aborted (6)
[fv-az1267-279:67104] Signal code:  (-6)
[fv-az1267-279:67104] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1c01045330]
[fv-az1267-279:67104] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1c0109eb2c]
[fv-az1267-279:67104] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1c0104527e]
[fv-az1267-279:67104] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1c010288ff]
[fv-az1267-279:67104] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1c014a5ff5]
[fv-az1267-279:67104] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1c014bb0da]
[fv-az1267-279:67104] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1c014a5a55]
[fv-az1267-279:67104] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1c014a5a6f]
[fv-az1267-279:67104] [ 8] plumed_master(+0x146dd)[0x55a060ceb6dd]
[fv-az1267-279:67104] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1c0102a1ca]
[fv-az1267-279:67104] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1c0102a28b]
[fv-az1267-279:67104] [11] plumed_master(+0x15365)[0x55a060cec365]
[fv-az1267-279:67104] *** End of error message ***
</pre>
{% endraw %}
