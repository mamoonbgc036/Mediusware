<template>
     <div class="card-body">
            <div class="table-response">
                <table class="table">
                    <thead>
                    <tr>
                        <th>#</th>
                        <th>Title</th>
                        <th>Description</th>
                        <th>Variant</th>
                        <th width="150px">Action</th>
                    </tr>
                    </thead>

                    <tbody>

                    <tr>
                        <td>1</td>
                        <td>T-Shirt <br> Created at : 25-Aug-2020</td>
                        <td>Quality product in low cost and comfortable.</td>
                        <td>
                            <dl class="row mb-0" style="height: 80px; overflow: hidden" id="variant">

                                <dt class="col-sm-3 pb-0">
                                    SM/ Red/ V-Nick
                                </dt>
                                <dd class="col-sm-9">
                                    <dl class="row mb-0">
                                        <dt class="col-sm-4 pb-0">Price : 200 </dt>
                                        <dd class="col-sm-8 pb-0">InStock : </dd>
                                    </dl>
                                </dd>
                            </dl>
                            <button onclick="$('#variant').toggleClass('h-auto')" class="btn btn-sm btn-link">Show more</button>
                        </td>
                        <td>
                            <div class="btn-group btn-group-sm">
                                <a href="" class="btn btn-success">Edit</a>
                            </div>
                        </td>
                        
                    </tr>
                    </tbody>

                </table>
            </div>

        </div>
</template>
<script>
</script>