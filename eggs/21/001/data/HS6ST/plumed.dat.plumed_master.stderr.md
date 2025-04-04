**Project ID:** [plumID:21.001]({{ '/' | absolute_url }}eggs/21/001/)  
Stderr for source:  HS6ST/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @48 : keyword ARG is compulsory for this action
[fv-az805-507:12166] *** Process received signal ***
[fv-az805-507:12166] Signal: Aborted (6)
[fv-az805-507:12166] Signal code:  (-6)
[fv-az805-507:12166] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2f85645330]
[fv-az805-507:12166] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2f8569eb2c]
[fv-az805-507:12166] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2f8564527e]
[fv-az805-507:12166] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2f856288ff]
[fv-az805-507:12166] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2f85aa5ff5]
[fv-az805-507:12166] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2f85abb0da]
[fv-az805-507:12166] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2f85aa5a55]
[fv-az805-507:12166] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2f85aa5a6f]
[fv-az805-507:12166] [ 8] plumed_master(+0x146dd)[0x562a577356dd]
[fv-az805-507:12166] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2f8562a1ca]
[fv-az805-507:12166] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2f8562a28b]
[fv-az805-507:12166] [11] plumed_master(+0x15365)[0x562a57736365]
[fv-az805-507:12166] *** End of error message ***
</pre>
{% endraw %}
