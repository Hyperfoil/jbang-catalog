# Hyperfoil JBang Catalog 

This is a catalog of JBang scripts for Hyperfoil.

## Usage

To use the scripts from this catalog you need to have [JBang](https://www.jbang.dev/) installed.

Example of running the `wrk2` is as follows:

```bash
jbang wrk2@hyperfoil -t2 -c100 -d30s -R100 --latency http://localhost:8080
```

Example of running the `run` to execute a custom Hyperfoil benchmark:

```bash
jbang run@hyperfoil ./simple-benchmark.hf.yml
```

To list all the available scripts in the catalog you can use the following command:

```bash
jbang catalog list hyperfoil
```
