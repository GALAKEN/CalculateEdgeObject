# CalculateEdgeObject
Unity c# 

    float EgdgeObject()
    {
        Collider colliderObject = GetComponent<Collider>();
        if(colliderObject != null )
        {
            float fullObject = colliderObject.bounds.extents.z;
            float extentsObject = colliderObject.transform.position.z + fullObject;
        }
        else
        {
            Debug.Log("xw0lle:Fuck u're mother");
        }

        return 0;
    }
