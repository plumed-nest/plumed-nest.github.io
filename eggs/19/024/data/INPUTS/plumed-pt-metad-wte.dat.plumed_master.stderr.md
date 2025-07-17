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
[pkrvmq0rgcvqdmg:12989] *** Process received signal ***
[pkrvmq0rgcvqdmg:12989] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:12989] Signal code:  (-6)
[pkrvmq0rgcvqdmg:12989] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9a6ea45330]
[pkrvmq0rgcvqdmg:12989] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9a6ea9eb2c]
[pkrvmq0rgcvqdmg:12989] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9a6ea4527e]
[pkrvmq0rgcvqdmg:12989] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9a6ea288ff]
[pkrvmq0rgcvqdmg:12989] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9a6eea5ff5]
[pkrvmq0rgcvqdmg:12989] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9a6eebb0da]
[pkrvmq0rgcvqdmg:12989] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9a6eea5a55]
[pkrvmq0rgcvqdmg:12989] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9a6eea5a6f]
[pkrvmq0rgcvqdmg:12989] [ 8] plumed_master(+0x146dd)[0x557b129c36dd]
[pkrvmq0rgcvqdmg:12989] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9a6ea2a1ca]
[pkrvmq0rgcvqdmg:12989] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9a6ea2a28b]
[pkrvmq0rgcvqdmg:12989] [11] plumed_master(+0x15365)[0x557b129c4365]
[pkrvmq0rgcvqdmg:12989] *** End of error message ***
</pre>
{% endraw %}
