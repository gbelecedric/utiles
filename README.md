```javascript
                    <div class="container">
                        <div class="row" id="secs">
                            <div v-for="item in secretaire" class="col-md-2 col-sm-4 offset-1">
                                <div class="card secrecard component-card_3">
                                    <div class="card-body p-1">
                                        <div class="avatar avatar-xl">
                                            <img alt="avatar" :src=`${item.avatar}` class="rounded-circle" />
                                        </div>    
                                        <h5 class="text-dark text-center card-user_name"><i class="fas fa-circle connected"></i>   ${item.nom} ${item.prenom} </h5>
                                        
                                        <p class="card-user_occupation"><i class="fas fa-map-marker-alt"></i>  ${item.ville}</p>
                                        <div class="anotherInfo">
                                            <hr class="divider">
                                            <a style="pointer-events: visible;" :href=``+`${base_url}`+`/blabla/`+`${item.bloblo}`+`/`+`${item.blobli}`+`/`+`${item.vuk}`+`` class="justify-content-center d-flex text-left my-3">
                                                <img class="seeSecreProfil mr-2" src="{% static 'assetss/img/person.png'%}" alt="user ico">
                                                <p class="text-dark p-0 m-0"> Voir profil</p>
                                            </a>
                                            
                                            <a :href=``+`${base_url}`+`/bloblo/blibli/`+`${item.username}`+`` class="d-flex justify-content-center text-left">
                                                <img class=" seeSecreProfil mr-2" src="{% static 'assetss/img/message.png'%}" alt="user ico">
                                                <p class="text-dark "> Contacter</p>
                                            </a>
                                        </div>
                                        
                                    </div>
                                </div>
                            </div>
                        </div>                            
                    </div>
```






'''


'''



