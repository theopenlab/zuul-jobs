Fetch a Javascript content tarball back to be published.

A content tarball is one that contains built javascript/css artifacts,
such as but not limited to those produced by the webpack ArchivePlugin.

**Role Variables**

.. zuul:rolevar:: zuul_work_dir
   :default: {{ zuul.project.src_dir }}

   Directory to work in.
