##**Egde table**
node1
node2
Subtype1	activation;binding/association;dissociation;indirect effect;NULL
Subtype2	dephsophorylation;phosphorylation;NULL
EdgeType	-->;---;..>;--|;-+-;NULL
Source	KEGG_XXX;CST_XXX

##**Node table**
node
type	protein;DNA/RNA;compound;pathway
gene(for protein node only)
cellular_component	cytosol;nucleus;plasma membrane;mitochondrial membrane;ER membrane;else?

##**Source table**
source	KEGG;CST
PathwayID
PathwayName
Label
Link
comment


#_NOTE_
1. All tables shall be comma seperated files (.csv);
2. About EdgeType (for KEGG orginated edges only):
--> activation
--| inhibition
..> indirect effect
--- binding
-+- association 
