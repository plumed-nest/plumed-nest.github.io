**Project ID:** [plumID:20.033]({{ '/' | absolute_url }}eggs/20/033/)  
Stderr for source:  ANALYSIS/plumed_histogram.dat   
Download: [zipped raw stdout](plumed_histogram.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_histogram.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @30 : keyword ARG is compulsory for this action
[fv-az1267-279:67953] *** Process received signal ***
[fv-az1267-279:67953] Signal: Aborted (6)
[fv-az1267-279:67953] Signal code:  (-6)
[fv-az1267-279:67953] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9085645330]
[fv-az1267-279:67953] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f908569eb2c]
[fv-az1267-279:67953] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f908564527e]
[fv-az1267-279:67953] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f90856288ff]
[fv-az1267-279:67953] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9085aa5ff5]
[fv-az1267-279:67953] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9085abb0da]
[fv-az1267-279:67953] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9085aa5a55]
[fv-az1267-279:67953] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9085aa5a6f]
[fv-az1267-279:67953] [ 8] plumed_master(+0x146dd)[0x55b0680ed6dd]
[fv-az1267-279:67953] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f908562a1ca]
[fv-az1267-279:67953] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f908562a28b]
[fv-az1267-279:67953] [11] plumed_master(+0x15365)[0x55b0680ee365]
[fv-az1267-279:67953] *** End of error message ***
</pre>
{% endraw %}
