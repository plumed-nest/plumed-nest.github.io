**Project ID:** [plumID:19.024]({{ '/' | absolute_url }}eggs/19/024/)  
Stderr for source:  INPUTS/plumed-pt-metad-wte.dat   
Download: [zipped raw stdout](plumed-pt-metad-wte.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-pt-metad-wte.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Grid.cpp:655) static std::unique_ptr<PLMD::GridBase> PLMD::GridBase::create(const std::string&, const std::vector<PLMD::Value*>&, PLMD::IFile&, bool, bool, bool)
+++ assertion failed: ifile.FieldExist( funcl )
no column labelled @6.bias in in grid input
[pkrvmberfyhpb9w:11685] *** Process received signal ***
[pkrvmberfyhpb9w:11685] Signal: Aborted (6)
[pkrvmberfyhpb9w:11685] Signal code:  (-6)
[pkrvmberfyhpb9w:11685] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7feafc645330]
[pkrvmberfyhpb9w:11685] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7feafc69eb2c]
[pkrvmberfyhpb9w:11685] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7feafc64527e]
[pkrvmberfyhpb9w:11685] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7feafc6288ff]
[pkrvmberfyhpb9w:11685] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7feafcaa5ff5]
[pkrvmberfyhpb9w:11685] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7feafcabb0da]
[pkrvmberfyhpb9w:11685] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7feafcaa5a55]
[pkrvmberfyhpb9w:11685] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7feafcaa5a6f]
[pkrvmberfyhpb9w:11685] [ 8] plumed_master(+0x146dd)[0x557f086ea6dd]
[pkrvmberfyhpb9w:11685] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7feafc62a1ca]
[pkrvmberfyhpb9w:11685] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7feafc62a28b]
[pkrvmberfyhpb9w:11685] [11] plumed_master(+0x15365)[0x557f086eb365]
[pkrvmberfyhpb9w:11685] *** End of error message ***
</pre>
{% endraw %}
