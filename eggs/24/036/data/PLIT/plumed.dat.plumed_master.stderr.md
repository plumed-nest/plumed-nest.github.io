**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @35 : keyword ARG is compulsory for this action
[fv-az1341-704:60489] *** Process received signal ***
[fv-az1341-704:60489] Signal: Aborted (6)
[fv-az1341-704:60489] Signal code:  (-6)
[fv-az1341-704:60489] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f07b6e45330]
[fv-az1341-704:60489] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f07b6e9eb2c]
[fv-az1341-704:60489] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f07b6e4527e]
[fv-az1341-704:60489] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f07b6e288ff]
[fv-az1341-704:60489] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f07b72a5ff5]
[fv-az1341-704:60489] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f07b72bb0da]
[fv-az1341-704:60489] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f07b72a5a55]
[fv-az1341-704:60489] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f07b72a5a6f]
[fv-az1341-704:60489] [ 8] plumed_master(+0x146dd)[0x55791d7bc6dd]
[fv-az1341-704:60489] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f07b6e2a1ca]
[fv-az1341-704:60489] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f07b6e2a28b]
[fv-az1341-704:60489] [11] plumed_master(+0x15365)[0x55791d7bd365]
[fv-az1341-704:60489] *** End of error message ***
</pre>
{% endraw %}
