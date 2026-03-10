**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  droplet/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:378) void PLMD::Keywords::use(std::string_view)
+++ assertion failed: reserved(k)
the ARG keyword is not reserved
[runnervm0kj6c:10478] *** Process received signal ***
[runnervm0kj6c:10478] Signal: Aborted (6)
[runnervm0kj6c:10478] Signal code:  (-6)
[runnervm0kj6c:10478] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6498045330]
[runnervm0kj6c:10478] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f649809eb2c]
[runnervm0kj6c:10478] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f649804527e]
[runnervm0kj6c:10478] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f64980288ff]
[runnervm0kj6c:10478] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f64984a5ff5]
[runnervm0kj6c:10478] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f64984bb0da]
[runnervm0kj6c:10478] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f64984a5a55]
[runnervm0kj6c:10478] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f64984a5a6f]
[runnervm0kj6c:10478] [ 8] plumed_master(+0x146dd)[0x557b995496dd]
[runnervm0kj6c:10478] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f649802a1ca]
[runnervm0kj6c:10478] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f649802a28b]
[runnervm0kj6c:10478] [11] plumed_master(+0x15365)[0x557b9954a365]
[runnervm0kj6c:10478] *** End of error message ***
</pre>
{% endraw %}
