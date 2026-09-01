**Project ID:** [plumID:25.012]({{ '/' | absolute_url }}eggs/25/012/)  
Stderr for source:  OPES_Enhanced_Sampling_with_Committor/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/DLLoader.cpp:50) void* PLMD::DLLoader::load(const std::string&)
Could not load library ./pytorch_model_bias.so
libxpmem.so.0: cannot open shared object file: No such file or directory
[runnervmgx7h7:04676] *** Process received signal ***
[runnervmgx7h7:04676] Signal: Aborted (6)
[runnervmgx7h7:04676] Signal code:  (-6)
[runnervmgx7h7:04676] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f30a6645330]
[runnervmgx7h7:04676] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f30a669ec0c]
[runnervmgx7h7:04676] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f30a664527e]
[runnervmgx7h7:04676] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f30a66288ff]
[runnervmgx7h7:04676] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f30a6aa5ff5]
[runnervmgx7h7:04676] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f30a6abb0da]
[runnervmgx7h7:04676] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f30a6aa5a55]
[runnervmgx7h7:04676] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f30a6aa5a6f]
[runnervmgx7h7:04676] [ 8] plumed(+0x146dd)[0x55ae3f84d6dd]
[runnervmgx7h7:04676] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f30a662a1ca]
[runnervmgx7h7:04676] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f30a662a28b]
[runnervmgx7h7:04676] [11] plumed(+0x15365)[0x55ae3f84e365]
[runnervmgx7h7:04676] *** End of error message ***
</pre>
{% endraw %}
