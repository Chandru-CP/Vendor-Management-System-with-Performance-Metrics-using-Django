sameple input format for the api

API:http://127.0.0.1:8000/api/vendors/
##same all input should give to PUT request also

content= {
        "id": 1,
        "name": "ABC Company",
        "contact_details": "123-456-7890",
        "address": "123 Main Street, City, Country",
        "vendor_code": "VEND001",
        "on_time_delivery_rate": 0.85,
        "quality_rating_avg": 4.5,
        "average_response_time": 24.5,
        "fulfillment_rate": 0.95
    }


api:http://127.0.0.1:8000/api/purchase_orders/
##same all input should give to PUT request  also
content={
    "id": 1,
    "po_number": "PO123456",
    "order_date": "2024-05-01T08:00:00Z",
    "delivery_date": "2024-05-15T08:00:00Z",
    "items": [
        {
            "name": "Product  d",
            "quantity": 10,
            "price": 20.0
        },
        {
            "name": "Product c",
            "quantity": 5,
            "price": 30.0
        }
    ],
    "quantity": 15,
    "status": "pending",
    "quality_rating": null,
    "issue_date": "2024-05-01T08:00:00Z",
    "acknowledgment_date": null,
    "vendor": 1
}



API:http://127.0.0.1:8000/api/vendors/1/performance/
content=
{
    "on_time_delivery_rate": 0.85,
    "quality_rating_avg": 4.5,
    "average_response_time": 24.5,
    "fulfillment_rate": 0.95
}
