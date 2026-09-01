**Project ID:** [plumID:19.024]({{ '/' | absolute_url }}eggs/19/024/)  
Stderr for source:  INPUTS/plumed-pt-metad-wte.dat   
Download: [zipped raw stdout](plumed-pt-metad-wte.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-pt-metad-wte.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Grid.cpp:655) static std::unique_ptr<PLMD::GridBase> PLMD::GridBase::create(const std::string&, const std::vector<PLMD::Value*>&, PLMD::IFile&, bool, bool, bool)
+++ assertion failed: ifile.FieldExist( funcl )
no column labelled @6.bias in in grid input
[runnervmgx7h7:07351] *** Process received signal ***
[runnervmgx7h7:07351] Signal: Aborted (6)
[runnervmgx7h7:07351] Signal code:  (-6)
[runnervmgx7h7:07351] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4bf7845330]
[runnervmgx7h7:07351] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4bf789ec0c]
[runnervmgx7h7:07351] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4bf784527e]
[runnervmgx7h7:07351] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4bf78288ff]
[runnervmgx7h7:07351] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4bf7ca5ff5]
[runnervmgx7h7:07351] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4bf7cbb0da]
[runnervmgx7h7:07351] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4bf7ca5a55]
[runnervmgx7h7:07351] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4bf7ca5a6f]
[runnervmgx7h7:07351] [ 8] plumed_master(+0x146dd)[0x555fdf8c26dd]
[runnervmgx7h7:07351] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4bf782a1ca]
[runnervmgx7h7:07351] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4bf782a28b]
[runnervmgx7h7:07351] [11] plumed_master(+0x15365)[0x555fdf8c3365]
[runnervmgx7h7:07351] *** End of error message ***
</pre>
{% endraw %}
