# <Siya Patil>: my first Phlex workflow

<!-- Replace everything in angle brackets. Delete these comments when you're done. -->

**Siya Patil: BMS College of Engineering, SIREN for Photon Visibility Modelling in ICARUS**

## What this does

Runs the C++ example workflow on 20 spills
and writes only the `sum` product with FORM.

## How to run it

From your build directory:

```bash
phlex -c ../dune-tech-phlex-sandbox/contributions/<you>/my-workflow.jsonnet --stage <you>
```

## What you should see

Registering FORM output module...
Configuration:
  output 'default': output.root (ROOT_TTREE)
FORM output module registered successfully

=== form_output_module::save_data_products ===
Creator: geometry_source:provide_geometry
Stage: siya-patil
Data cell: []
Number of products: 1
  Product: input/geometry
No configuration found for product: geometry
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_j
Stage: siya-patil
Data cell: [spill:1]
Number of products: 1
  Product: input/j
No configuration found for product: j
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_i
Stage: siya-patil
Data cell: [spill:1]
Number of products: 1
  Product: input/i
No configuration found for product: i
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_j
Stage: siya-patil
Data cell: [spill:2]
Number of products: 1
  Product: input/j
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_i
Stage: siya-patil
Data cell: [spill:2]
Number of products: 1
  Product: input/i
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: multiply_cpp:multiply
Stage: siya-patil
Data cell: [spill:1]
Number of products: 1
  Product: multiply_cpp:multiply/product
No configuration found for product: product
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: add_cpp:add
Stage: siya-patil
Data cell: [spill:1]
Number of products: 1
  Product: add_cpp:add/sum
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: add_cpp:add
Stage: siya-patil
Data cell: [spill:2]
Number of products: 1
  Product: add_cpp:add/sum
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: multiply_cpp:multiply
Stage: siya-patil
Data cell: [spill:2]
Number of products: 1
  Product: multiply_cpp:multiply/product
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_i
Stage: siya-patil
Data cell: [spill:3]
Number of products: 1
  Product: input/i
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_i
Stage: siya-patil
Data cell: [spill:4]
Number of products: 1
  Product: input/i
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_i
Stage: siya-patil
Data cell: [spill:5]
Number of products: 1
  Product: input/i
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_i
Stage: siya-patil
Data cell: [spill:6]
Number of products: 1
  Product: input/i
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_j
Stage: siya-patil
Data cell: [spill:3]
Number of products: 1
  Product: input/j
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: multiply_cpp:multiply
Stage: siya-patil
Data cell: [spill:3]
Number of products: 1
  Product: multiply_cpp:multiply/product
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: add_cpp:add
Stage: siya-patil
Data cell: [spill:3]
Number of products: 1
  Product: add_cpp:add/sum
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_j
Stage: siya-patil
Data cell: [spill:4]
Number of products: 1
  Product: input/j
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: multiply_cpp:multiply
Stage: siya-patil
Data cell: [spill:4]
Number of products: 1
  Product: multiply_cpp:multiply/product
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: add_cpp:add
Stage: siya-patil
Data cell: [spill:4]
Number of products: 1
  Product: add_cpp:add/sum
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_j
Stage: siya-patil
Data cell: [spill:5]
Number of products: 1
  Product: input/j
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: multiply_cpp:multiply
Stage: siya-patil
Data cell: [spill:5]
Number of products: 1
  Product: multiply_cpp:multiply/product
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: add_cpp:add
Stage: siya-patil
Data cell: [spill:5]
Number of products: 1
  Product: add_cpp:add/sum
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_j
Stage: siya-patil
Data cell: [spill:6]
Number of products: 1
  Product: input/j
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: multiply_cpp:multiply
Stage: siya-patil
Data cell: [spill:6]
Number of products: 1
  Product: multiply_cpp:multiply/product
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: add_cpp:add
Stage: siya-patil
Data cell: [spill:6]
Number of products: 1
  Product: add_cpp:add/sum
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_i
Stage: siya-patil
Data cell: [spill:7]
Number of products: 1
  Product: input/i
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_i
Stage: siya-patil
Data cell: [spill:8]
Number of products: 1
  Product: input/i
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_i
Stage: siya-patil
Data cell: [spill:9]
Number of products: 1
  Product: input/i
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_i
Stage: siya-patil
Data cell: [spill:10]
Number of products: 1
  Product: input/i
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_i
Stage: siya-patil
Data cell: [spill:11]
Number of products: 1
  Product: input/i
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_j
Stage: siya-patil
Data cell: [spill:7]
Number of products: 1
  Product: input/j
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: multiply_cpp:multiply
Stage: siya-patil
Data cell: [spill:7]
Number of products: 1
  Product: multiply_cpp:multiply/product
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: add_cpp:add
Stage: siya-patil
Data cell: [spill:7]
Number of products: 1
  Product: add_cpp:add/sum
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_j
Stage: siya-patil
Data cell: [spill:8]
Number of products: 1
  Product: input/j
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: multiply_cpp:multiply
Stage: siya-patil
Data cell: [spill:8]
Number of products: 1
  Product: multiply_cpp:multiply/product
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: add_cpp:add
Stage: siya-patil
Data cell: [spill:8]
Number of products: 1
  Product: add_cpp:add/sum
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_j
Stage: siya-patil
Data cell: [spill:9]
Number of products: 1
  Product: input/j
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: multiply_cpp:multiply
Stage: siya-patil
Data cell: [spill:9]
Number of products: 1
  Product: multiply_cpp:multiply/product
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: add_cpp:add
Stage: siya-patil
Data cell: [spill:9]
Number of products: 1
  Product: add_cpp:add/sum
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_j
Stage: siya-patil
Data cell: [spill:10]
Number of products: 1
  Product: input/j
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: multiply_cpp:multiply
Stage: siya-patil
Data cell: [spill:10]
Number of products: 1
  Product: multiply_cpp:multiply/product
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: add_cpp:add
Stage: siya-patil
Data cell: [spill:10]
Number of products: 1
  Product: add_cpp:add/sum
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_j
Stage: siya-patil
Data cell: [spill:11]
Number of products: 1
  Product: input/j
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: multiply_cpp:multiply
Stage: siya-patil
Data cell: [spill:11]
Number of products: 1
  Product: multiply_cpp:multiply/product
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: add_cpp:add
Stage: siya-patil
Data cell: [spill:11]
Number of products: 1
  Product: add_cpp:add/sum
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_j
Stage: siya-patil
Data cell: [spill:12]
Number of products: 1
  Product: input/j
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_j
Stage: siya-patil
Data cell: [spill:13]
Number of products: 1
  Product: input/j
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_i
Stage: siya-patil
Data cell: [spill:12]
Number of products: 1
  Product: input/i
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: multiply_cpp:multiply
Stage: siya-patil
Data cell: [spill:12]
Number of products: 1
  Product: multiply_cpp:multiply/product
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: add_cpp:add
Stage: siya-patil
Data cell: [spill:12]
Number of products: 1
  Product: add_cpp:add/sum
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_i
Stage: siya-patil
Data cell: [spill:13]
Number of products: 1
  Product: input/i
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: multiply_cpp:multiply
Stage: siya-patil
Data cell: [spill:13]
Number of products: 1
  Product: multiply_cpp:multiply/product
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: add_cpp:add
Stage: siya-patil
Data cell: [spill:13]
Number of products: 1
  Product: add_cpp:add/sum
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_j
Stage: siya-patil
Data cell: [spill:14]
Number of products: 1
  Product: input/j
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_j
Stage: siya-patil
Data cell: [spill:15]
Number of products: 1
  Product: input/j
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_i
Stage: siya-patil
Data cell: [spill:14]
Number of products: 1
  Product: input/i
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: multiply_cpp:multiply
Stage: siya-patil
Data cell: [spill:14]
Number of products: 1
  Product: multiply_cpp:multiply/product
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: add_cpp:add
Stage: siya-patil
Data cell: [spill:14]
Number of products: 1
  Product: add_cpp:add/sum
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_i
Stage: siya-patil
Data cell: [spill:15]
Number of products: 1
  Product: input/i
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: multiply_cpp:multiply
Stage: siya-patil
Data cell: [spill:15]
Number of products: 1
  Product: multiply_cpp:multiply/product
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: add_cpp:add
Stage: siya-patil
Data cell: [spill:15]
Number of products: 1
  Product: add_cpp:add/sum
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_i
Stage: siya-patil
Data cell: [spill:16]
Number of products: 1
  Product: input/i
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_j
Stage: siya-patil
Data cell: [spill:16]
Number of products: 1
  Product: input/j
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: multiply_cpp:multiply
Stage: siya-patil
Data cell: [spill:16]
Number of products: 1
  Product: multiply_cpp:multiply/product
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_i
Stage: siya-patil
Data cell: [spill:17]
Number of products: 1
  Product: input/i
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: add_cpp:add
Stage: siya-patil
Data cell: [spill:16]
Number of products: 1
  Product: add_cpp:add/sum
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_i
Stage: siya-patil
Data cell: [spill:18]
Number of products: 1
  Product: input/i
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_j
Stage: siya-patil
Data cell: [spill:17]
Number of products: 1
  Product: input/j
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_j
Stage: siya-patil
Data cell: [spill:18]
Number of products: 1
  Product: input/j
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_i
Stage: siya-patil
Data cell: [spill:19]
Number of products: 1
  Product: input/i
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_j
Stage: siya-patil
Data cell: [spill:19]
Number of products: 1
  Product: input/j
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_i
Stage: siya-patil
Data cell: [spill:20]
Number of products: 1
  Product: input/i
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: add_cpp:add
Stage: siya-patil
Data cell: [spill:17]
Number of products: 1
  Product: add_cpp:add/sum
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: multiply_cpp:multiply
Stage: siya-patil
Data cell: [spill:18]
Number of products: 1
  Product: multiply_cpp:multiply/product
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: multiply_cpp:multiply
Stage: siya-patil
Data cell: [spill:17]
Number of products: 1
  Product: multiply_cpp:multiply/product
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: multiply_cpp:multiply
Stage: siya-patil
Data cell: [spill:19]
Number of products: 1
  Product: multiply_cpp:multiply/product
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: add_cpp:add
Stage: siya-patil
Data cell: [spill:19]
Number of products: 1
  Product: add_cpp:add/sum
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: add_cpp:add
Stage: siya-patil
Data cell: [spill:18]
Number of products: 1
  Product: add_cpp:add/sum
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_j
Stage: siya-patil
Data cell: [spill:20]
Number of products: 1
  Product: input/j
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: add_cpp:add
Stage: siya-patil
Data cell: [spill:20]
Number of products: 1
  Product: add_cpp:add/sum
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: multiply_cpp:multiply
Stage: siya-patil
Data cell: [spill:20]
Number of products: 1
  Product: multiply_cpp:multiply/product
Wrote 1 products to FORM
[2026-10-27 12:10:52.655] [info] 

Seen layers:

  job
   │ 
   └ spill: 20


## One thing I learned today

Debugging (although I could not everything)

## One word for today

Challenging
