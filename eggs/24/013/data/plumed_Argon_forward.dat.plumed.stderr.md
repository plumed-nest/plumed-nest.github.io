**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_forward.dat   
Download: [zipped raw stdout](plumed_Argon_forward.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_forward.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[fv-az1983-395:60930] *** Process received signal ***
[fv-az1983-395:60930] Signal: Aborted (6)
[fv-az1983-395:60930] Signal code:  (-6)
[fv-az1983-395:60930] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f290fa45330]
[fv-az1983-395:60930] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f290fa9eb2c]
[fv-az1983-395:60930] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f290fa4527e]
[fv-az1983-395:60930] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f290fa288ff]
[fv-az1983-395:60930] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f290fea5ff5]
[fv-az1983-395:60930] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f290febb0da]
[fv-az1983-395:60930] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f290fea5a55]
[fv-az1983-395:60930] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f290fea5a6f]
[fv-az1983-395:60930] [ 8] plumed(+0x146dd)[0x557a0c0026dd]
[fv-az1983-395:60930] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f290fa2a1ca]
[fv-az1983-395:60930] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f290fa2a28b]
[fv-az1983-395:60930] [11] plumed(+0x15365)[0x557a0c003365]
[fv-az1983-395:60930] *** End of error message ***
</pre>
{% endraw %}
