curl --location 'https://api.gectaro.com/v1/projects/118846/resource-requests?expand=projectTasksResource.commentsCount%2CprojectTasksResource.newCommentsCount%2Cis_delivered%2CresourceOrderItems.resourceOrder.contractor%2Cdeliver_until_date%2CresourceRequestCount%2CprojectTasksResource.contractor%2CprojectTasksResource.typeBudget%2CprojectTasksResource.projectTask.projectStage&order=asc&sort=needed_at&page=1&per-page=20' \
--header 'Authorization: Bearer fexrwQ7FJDvLfrHOprE0IoXXl-pz-w-g' \
--header 'Cookie: _csrf=pqfQGy2BLHAwMr6UPWUMsrO77QNQh2sd' \
--data ''
//GET ЗАПРОС НА СОЗДАНИЕ ЗАЯВКИ
curl --location 'https://api.gectaro.com/v1/projects/118846/resource-requests?expand=projectTasksResource.commentsCount%2CprojectTasksResource.newCommentsCount%2Cis_delivered%2CresourceOrderItems.resourceOrder.contractor%2Cdeliver_until_date%2CresourceRequestCount%2CprojectTasksResource.contractor%2CprojectTasksResource.typeBudget%2CprojectTasksResource.projectTask.projectStage&order=asc&sort=needed_at&page=1&per-page=20' \
--header 'Content-Type: application/json' \
--header 'Authorization: Bearer fexrwQ7FJDvLfrHOprE0IoXXl-pz-w-g' \
--header 'Cookie: _csrf=5_u-QRAOMBg4IZ7XbFDhQvorOsPjo8VL' \
--data '{
        
        "project_tasks_resource_id": 15973235,
        "volume": "-999.0000000000",
        "cost": "-444.0000000000",
        "batch_number": null,
        "batch_parent_request_id": null,
        "is_over_budget": true,
        "created_at": 1747984897,
        "updated_at": 1749017965,
        "user_id": 27090,
        "needed_at": 1733295600,
        "created_by": 27090,
        "sort_order": 0,
        "projectTasksResource": {
            "id": 15973235,
            "project_task_id": null,
            "contractor_id": null,
            "project_id": 118846,
            "type": 2,
            "number": 968690,
            "sort_order": null,
            "name": "болтик",
            "url": null,
            "valuation_id": null,
            "volume": 0,
            "write_off": 0,
            "is_write_off_over": false,
            "unit_measure_id": 124,
            "price": 444,
            "price_with_markup": 0,
            "cost": 0,
            "cost_with_markup": 0,
            "markup": 0,
            "volume_fact": null,
            "cost_fact": null,
            "price_fact": null,
            "cost_with_markup_fact": null,
            "price_with_markup_fact": null,
            "created_at": 1747984893,
            "updated_at": 1747984893,
            "resourceRequestCount": 1,
            "typeBudget": "over_budget",
            "laborResourceVolume": null,
            "laborResourceSum": null,
            "projectTask": null,
            "commentsCount": 0,
            "newCommentsCount": 0
        },
        "resourceOrderItems": [],
        "deliver_until_date": null,
        "is_delivered": false
}'
//POST ЗАПРОС НА СОЗДАНИЕ ЗАЯВКИ
curl --location --request DELETE 'https://api.gectaro.com/v1/projects/118846/resource-requests/11397841' \
--header 'Authorization: Bearer fexrwQ7FJDvLfrHOprE0IoXXl-pz-w-g' \
--header 'Cookie: _csrf=PteQbrK31KPp95S2IizU-6uLSAakmaT9' \
--data ''
// DELETE ЗАВПРОС НА СОЗДАНИЕ ЗАЯВКИ
