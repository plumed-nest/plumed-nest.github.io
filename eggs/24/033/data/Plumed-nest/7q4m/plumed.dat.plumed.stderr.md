**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4m/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[fv-az1267-279:60459] *** Process received signal ***
[fv-az1267-279:60459] Signal: Aborted (6)
[fv-az1267-279:60459] Signal code:  (-6)
[fv-az1267-279:60459] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f597ce45330]
[fv-az1267-279:60459] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f597ce9eb2c]
[fv-az1267-279:60459] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f597ce4527e]
[fv-az1267-279:60459] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f597ce288ff]
[fv-az1267-279:60459] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f597d2a5ff5]
[fv-az1267-279:60459] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f597d2bb0da]
[fv-az1267-279:60459] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f597d2a5a55]
[fv-az1267-279:60459] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f597d2a5a6f]
[fv-az1267-279:60459] [ 8] plumed(+0x146dd)[0x55d6713866dd]
[fv-az1267-279:60459] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f597ce2a1ca]
[fv-az1267-279:60459] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f597ce2a28b]
[fv-az1267-279:60459] [11] plumed(+0x15365)[0x55d671387365]
[fv-az1267-279:60459] *** End of error message ***
</pre>
{% endraw %}
