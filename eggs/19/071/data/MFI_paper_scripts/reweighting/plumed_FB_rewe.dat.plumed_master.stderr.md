**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/reweighting/plumed_FB_rewe.dat   
(download [zipped raw stdout](plumed_FB_rewe.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Grid.cpp:565, function static std::unique_ptr<PLMD::GridBase> PLMD::GridBase::create(const string&, const std::vector<PLMD::Value*>&, PLMD::IFile&, bool, bool, bool)
+++ assertion failed: ifile.FieldExist( funcl )
+++ message follows +++
no column labelled metad.bias in in grid input
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12357] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12357] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12357] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12357] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f235ee3a4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12357] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f235ee3a428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12357] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f235ee3c02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12357] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f235f47484d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12357] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f235f4726b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12357] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f235f472701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12357] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x49)[0x7f235f472969]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12357] [ 7] plumed_master[0x40a072]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12357] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f235ee25830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12357] [ 9] plumed_master[0x40a0e9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12357] *** End of error message ***
</pre>
{% endraw %}
