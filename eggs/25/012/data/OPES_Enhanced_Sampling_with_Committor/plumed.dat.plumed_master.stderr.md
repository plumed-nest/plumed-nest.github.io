**Project ID:** [plumID:25.012]({{ '/' | absolute_url }}eggs/25/012/)  
Stderr for source:  OPES_Enhanced_Sampling_with_Committor/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/DLLoader.cpp:50) void* PLMD::DLLoader::load(const std::string&)
Could not load library ./pytorch_model_bias.so
libxpmem.so.0: cannot open shared object file: No such file or directory
[pkrvmxyh4eaekms:05592] *** Process received signal ***
[pkrvmxyh4eaekms:05592] Signal: Aborted (6)
[pkrvmxyh4eaekms:05592] Signal code:  (-6)
[pkrvmxyh4eaekms:05592] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc7ec045330]
[pkrvmxyh4eaekms:05592] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc7ec09eb2c]
[pkrvmxyh4eaekms:05592] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc7ec04527e]
[pkrvmxyh4eaekms:05592] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc7ec0288ff]
[pkrvmxyh4eaekms:05592] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc7ec4a5ff5]
[pkrvmxyh4eaekms:05592] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc7ec4bb0da]
[pkrvmxyh4eaekms:05592] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc7ec4a5a55]
[pkrvmxyh4eaekms:05592] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc7ec4a5a6f]
[pkrvmxyh4eaekms:05592] [ 8] plumed_master(+0x146dd)[0x5604ef82b6dd]
[pkrvmxyh4eaekms:05592] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc7ec02a1ca]
[pkrvmxyh4eaekms:05592] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc7ec02a28b]
[pkrvmxyh4eaekms:05592] [11] plumed_master(+0x15365)[0x5604ef82c365]
[pkrvmxyh4eaekms:05592] *** End of error message ***
</pre>
{% endraw %}
