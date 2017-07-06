# facet
Name of a lement in facet

I need help about how to add description on facet, here I will put my code so you could see what I am thinking :

List<Facet> facetsExecutor = findFacets("executorFaceting", "caseFileUserApps.activeUsers.executor", fullTextQuery, queryBuilder, includeZeroCounts);
		addMoreFacets(najdeniFaceti, facetsExecutor, rb.getString("com..........executor"));
		for(int i=0;i<facetsExecutor.size();i++)
		{
			String name=facetsExecutor.get(i).getValue();
			setDescription(name); //The method setDescription(name) is undefined for the type HibernateIndexSearch
		}
 
Could someone help me, because I need the look when my mouse is over the name of the element in the facet to show a field with specified text(name of the element in the facet)???
