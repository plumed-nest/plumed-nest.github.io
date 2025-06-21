**Project ID:** [plumID:23.044]({{ '/' | absolute_url }}eggs/23/044/)  
Stderr for source:  plumed_files/reweight_md.dat   
Download: [zipped raw stdout](reweight_md.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweight_md.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @31 : keyword ARG is compulsory for this action
[pkrvmxyh4eaekms:06424] *** Process received signal ***
[pkrvmxyh4eaekms:06424] Signal: Aborted (6)
[pkrvmxyh4eaekms:06424] Signal code:  (-6)
[pkrvmxyh4eaekms:06424] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdd04045330]
[pkrvmxyh4eaekms:06424] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdd0409eb2c]
[pkrvmxyh4eaekms:06424] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdd0404527e]
[pkrvmxyh4eaekms:06424] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdd040288ff]
[pkrvmxyh4eaekms:06424] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdd044a5ff5]
[pkrvmxyh4eaekms:06424] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdd044bb0da]
[pkrvmxyh4eaekms:06424] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdd044a5a55]
[pkrvmxyh4eaekms:06424] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdd044a5a6f]
[pkrvmxyh4eaekms:06424] [ 8] plumed_master(+0x146dd)[0x56177cebc6dd]
[pkrvmxyh4eaekms:06424] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdd0402a1ca]
[pkrvmxyh4eaekms:06424] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdd0402a28b]
[pkrvmxyh4eaekms:06424] [11] plumed_master(+0x15365)[0x56177cebd365]
[pkrvmxyh4eaekms:06424] *** End of error message ***
</pre>
{% endraw %}
