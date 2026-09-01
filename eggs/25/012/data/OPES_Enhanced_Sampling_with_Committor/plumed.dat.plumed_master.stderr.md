**Project ID:** [plumID:25.012]({{ '/' | absolute_url }}eggs/25/012/)  
Stderr for source:  OPES_Enhanced_Sampling_with_Committor/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/DLLoader.cpp:50) void* PLMD::DLLoader::load(const std::string&)
Could not load library ./pytorch_model_bias.so
libxpmem.so.0: cannot open shared object file: No such file or directory
[runnervmgx7h7:04691] *** Process received signal ***
[runnervmgx7h7:04691] Signal: Aborted (6)
[runnervmgx7h7:04691] Signal code:  (-6)
[runnervmgx7h7:04691] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbcdce45330]
[runnervmgx7h7:04691] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbcdce9ec0c]
[runnervmgx7h7:04691] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbcdce4527e]
[runnervmgx7h7:04691] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbcdce288ff]
[runnervmgx7h7:04691] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbcdd2a5ff5]
[runnervmgx7h7:04691] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbcdd2bb0da]
[runnervmgx7h7:04691] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbcdd2a5a55]
[runnervmgx7h7:04691] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbcdd2a5a6f]
[runnervmgx7h7:04691] [ 8] plumed_master(+0x146dd)[0x55c516a446dd]
[runnervmgx7h7:04691] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbcdce2a1ca]
[runnervmgx7h7:04691] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbcdce2a28b]
[runnervmgx7h7:04691] [11] plumed_master(+0x15365)[0x55c516a45365]
[runnervmgx7h7:04691] *** End of error message ***
</pre>
{% endraw %}
