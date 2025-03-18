**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  droplet/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:372) void PLMD::Keywords::use(std::string_view)
+++ assertion failed: reserved(k)
the ARG keyword is not reserved
[fv-az1267-279:66992] *** Process received signal ***
[fv-az1267-279:66992] Signal: Aborted (6)
[fv-az1267-279:66992] Signal code:  (-6)
[fv-az1267-279:66992] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2110845330]
[fv-az1267-279:66992] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f211089eb2c]
[fv-az1267-279:66992] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f211084527e]
[fv-az1267-279:66992] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f21108288ff]
[fv-az1267-279:66992] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2110ca5ff5]
[fv-az1267-279:66992] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2110cbb0da]
[fv-az1267-279:66992] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2110ca5a55]
[fv-az1267-279:66992] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2110ca5a6f]
[fv-az1267-279:66992] [ 8] plumed_master(+0x146dd)[0x55ca1c7d26dd]
[fv-az1267-279:66992] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f211082a1ca]
[fv-az1267-279:66992] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f211082a28b]
[fv-az1267-279:66992] [11] plumed_master(+0x15365)[0x55ca1c7d3365]
[fv-az1267-279:66992] *** End of error message ***
</pre>
{% endraw %}
