# Copyright (c) 2016 - present Facebook, Inc.
# All rights reserved.
#
# This source code is licensed under the BSD style license found in the
# LICENSE file in the root directory of this source tree. An additional grant
# of patent rights can be found in the PATENTS file in the same directory.

TESTS_DIR = ../../..

ANALYZER = checkers
INFER_OPTIONS = --biabduction-only --android-harness --no-filtering --debug-exceptions
INFERPRINT_OPTIONS = --issues-fields "file,procedure,line_offset,bug_type" --issues-tests
SOURCES = \
  BasicHarnessActivity.java \

include $(TESTS_DIR)/javac.make
