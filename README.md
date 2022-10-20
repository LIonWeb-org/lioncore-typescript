# README

TypeScript implementation for LIonWeb standards - currently: the `lioncore` meta-metamodel in [`src/m3/types.ts`](./src/m3/types.ts).


## Building

Run [`watch-check-meta-circularity.sh`](./watch-check-meta-circularity.sh) to generate a PlantUML file [`plantUML/metametamodel-gen.puml`](./plantUML/metametamodel-gen.puml) from the meta-circular definition of `lioncore` in [`src/m3/meta-circularity.ts`](./src/m3/meta-circularity.ts).
This generated PlantUML file can then be compared with the target file [`plantUML/metametamodel-target.puml`](./plantUML/metametamodel-target.puml) - they should have the same contents.
(The latter is slightly-modified version of [this one](https://github.com/LIonWeb-org/organization/blob/main/lioncore/metametamodel.puml).)


## Dev dependencies

* [Deno](https://deno.land/): {Java|Type}Script runtime
* (optional) [PlantUML](https://plantuml.com/)
