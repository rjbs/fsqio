
scala_record_library(
  name = 'gen',
  sources = globs('*.thrift'),
  tags = [
    'fscommon',
    'opensource',
    'dependencies_must_have:fscommon',
    'dependencies_must_have:opensource',
  ],
  dependencies = [
    'src/jvm/io/fsq/spindle/runtime',
  ],
)

# Required to bring the thrift files into an integration test's chroot.
files(
  name = 'files',
  sources = globs('*thrift'),
  scope="runtime",
)
