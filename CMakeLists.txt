# ─────────────────────────────────────────────────────────────────────────────┐
# ISC License
#
# Copyright (c) 2024 サイトー <https://zero.ms>
#
# Permission to use, copy, modify, and/or distribute this software for any
# purpose with or without fee is hereby granted, provided that the above
# copyright notice and this permission notice appear in all copies.
#
# THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH
# REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY
# AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT,
# INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM
# LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR
# OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR
# PERFORMANCE OF THIS SOFTWARE.
# ─────────────────────────────────────────────────────────────────────────────┘

cmake_minimum_required (VERSION 3.10)

project (Sea)

set (CMAKE_EXPORT_COMPILE_COMMANDS ON)

include_directories (${CMAKE_CURRENT_SOURCE_DIR})

add_executable (sea ${CMAKE_CURRENT_SOURCE_DIR}/demo/list.c)
