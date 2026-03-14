using UnityEngine;

public class DataVisualizer : MonoBehaviour
{
    public GameObject barPrefab;

    float[] dataset = {3f, 7f, 2f, 9f, 5f, 6f, 8f};

    void Start()
    {
        GenerateBars();
    }

    void GenerateBars()
    {
        for (int i = 0; i < dataset.Length; i++)
        {
            float height = dataset[i];

            GameObject bar = Instantiate(barPrefab);

            bar.transform.position = new Vector3(i * 2f, height / 2f, 0);

            bar.transform.localScale = new Vector3(1f, height, 1f);
        }
    }
}
