**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  DIDE-water/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @47 : keyword ARG is compulsory for this action
[fv-az1341-704:60447] *** Process received signal ***
[fv-az1341-704:60447] Signal: Aborted (6)
[fv-az1341-704:60447] Signal code:  (-6)
[fv-az1341-704:60447] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f51a9a45330]
[fv-az1341-704:60447] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f51a9a9eb2c]
[fv-az1341-704:60447] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f51a9a4527e]
[fv-az1341-704:60447] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f51a9a288ff]
[fv-az1341-704:60447] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f51a9ea5ff5]
[fv-az1341-704:60447] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f51a9ebb0da]
[fv-az1341-704:60447] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f51a9ea5a55]
[fv-az1341-704:60447] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f51a9ea5a6f]
[fv-az1341-704:60447] [ 8] plumed_master(+0x146dd)[0x55f6c173e6dd]
[fv-az1341-704:60447] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f51a9a2a1ca]
[fv-az1341-704:60447] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f51a9a2a28b]
[fv-az1341-704:60447] [11] plumed_master(+0x15365)[0x55f6c173f365]
[fv-az1341-704:60447] *** End of error message ***
</pre>
{% endraw %}
